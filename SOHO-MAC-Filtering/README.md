# SOHO Network Security - MAC Address Filtering Lab

A Cisco Packet Tracer simulation demonstrating a Small Office/Home Office (SOHO) network deployment featuring local network infrastructure, external WAN connectivity, and an incident response scenario utilizing MAC address filtering.

## 🌐 Network Topology Overview

The network architecture consists of three primary segments as shown in `image_8c2f60.png`:

1. **Local Area Network (LAN):** 
   * End devices including an `office pc`, `Laptop`, `Server`, and `Printer`.
   * Centralized connection via a Layer 2 **Switch**.
2. **Gateway:** 
   * A **SOHO Router** acting as the boundary device managing traffic between the internal network and external resources.
3. **Wide Area Network (WAN) Edge:**
   * High-speed edge connectivity achieved via a **Cable Modem** routing out to the external **Cloud**.

---

## 🔒 Cybersecurity Incident Scenario

### The Threat
An unauthorized external entity (`suspicious laptop`) managed to compromise the security perimeter after acquiring the **SOHO router's passkey**. 

### Incident Response & Mitigation
To prevent unauthorized access and secure the network, the administrator implemented immediate layer-2 hardware access controls:
* **Action taken:** Configured **MAC Address Filtering** directly on the SOHO Router.
* **Result:** The threat actor's specific hardware address was blacklisted/blocked immediately, cutting off network access despite them possessing the wireless passphrase.

---

## 🚀 Features & Concepts Demonstrated

* **SOHO Architecture:** Designing standard LAN/WAN boundaries with correct physical media selection (Straight-through, Coaxial, and Serial/DCE simulation cables).
* **Layer 2 Security:** Implementing hardware-level access control lists (MAC filtering) to enhance wireless/local boundary protection.
* **Network Infrastructure Services:** Structuring an environment capable of internal routing, NAT/PAT boundary translation, and endpoint addressing.

---

## 🛠️ How to Run the Lab

1. Download and install **Cisco Packet Tracer**.
2. Clone this repository or download the `.pkt` file.
3. Open the file in Packet Tracer to inspect device configurations, routing tables, and the router security setup.
