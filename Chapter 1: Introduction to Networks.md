---

# 📘 CompTIA Network+ – Chapter 1: Introduction to Networks

Explain the characteristics of network topologies and network types

---

## 🔹 Network Topologies (Physical & Logical)

1. **Bus Topology**

   * Single backbone cable connecting all devices.
   * Cheap but a single cable failure can bring the whole network down.

2. **Star / Hub-and-Spoke Topology**

   * All devices connect to a central hub/switch.
   * Easy to add devices, simple troubleshooting.

3. **Ring Topology**

   * Devices connected in a loop.
   * Data travels one direction. One break = network issue.

4. **Mesh Topology**

   * Every device connects to many others.
   * **Full Mesh** → every device linked to all.
   * **Partial Mesh** → some devices linked.
   * Very fault-tolerant but expensive.

5. **Hybrid Topology**

   * Combination of multiple topologies (e.g., Star + Bus).
   * Common in modern networks.

---

## 🔹 Network Types & Characteristics

1. **Peer-to-Peer (P2P)**

   * No central server; all devices are equal.
   * Good for small networks, but weak security.

2. **Client-Server**

   * Centralized server manages resources and security.
   * Scalable, secure, used in large networks.

3. **LAN (Local Area Network)**

   * Small area (home, office).
   * Usually Ethernet or Wi-Fi.

4. **WLAN (Wireless LAN)**

   * LAN using Wi-Fi.
   * Provides mobility but less secure.

5. **PAN (Personal Area Network)**

   * Very small area (few meters).
   * Examples: Bluetooth, USB tethering.

6. **CAN (Campus Area Network)**

   * Covers multiple buildings (universities, corporate campuses).

7. **MAN (Metropolitan Area Network)**

   * Covers a city or metro region.
   * Uses fiber-based metro-optical networks.

8. **WAN (Wide Area Network)**

   * Covers large geographic areas.
   * Internet = largest WAN.

9. **SAN (Storage Area Network)**

   * High-speed network connecting servers ↔ storage arrays.

10. **SD-WAN (Software-Defined WAN)**

    * Software-managed WAN.
    * Integrates MPLS, LTE, broadband → cheaper & flexible.

11. **MPLS (Multiprotocol Label Switching)**

    * Labels packets for fast forwarding.
    * Prioritizes traffic (e.g., voice > data).

12. **mGRE (Multipoint Generic Routing Encapsulation)**

    * Dynamic VPN tunneling protocol.
    * Creates/tears down tunnels on demand.

---

## 🔹 Service-Related Entry Points

1. **Demarcation Point (Demarc)**

   * Boundary where ISP responsibility ends and customer begins.

2. **Smart Jack**

   * ISP device at the demarc for testing & diagnostics.

---

## 🔹 Provider Links

1. **DSL (Digital Subscriber Line)** → Internet over telephone lines.
2. **Cable Internet** → Internet over cable TV lines.
3. **Leased Line** → Dedicated, secure, private line (expensive).
4. **Satellite** → Remote areas, but high latency.
5. **Metro-Optical Network** → High-speed city-wide fiber.

---

## 🔹 Virtual Network Concepts

1. **vSwitch (Virtual Switch)**

   * Software-based switch for virtual machines.

2. **vNIC (Virtual Network Interface Card)**

   * Virtual NIC for VMs to connect to a network.

3. **NFV (Network Function Virtualization)**

   * Network services (router, firewall, load balancer) running as software.

4. **Hypervisor**

   * Software that runs multiple VMs on one physical server.
   * Examples: VMware ESXi, Microsoft Hyper-V.

---

## 📌 Quick Summary (One-liners for Fast Revision)

* **Bus** = One backbone, cheap but risky.
* **Star** = Central hub/switch, scalable.
* **Ring** = Loop, one failure = problem.
* **Mesh** = Fault-tolerant, costly.
* **Hybrid** = Mixed topology.
* **P2P** = No central control.
* **Client-Server** = Centralized, secure.
* **LAN/WLAN** = Local coverage.
* **WAN** = Global coverage.
* **PAN** = Very small, personal devices.
* **CAN** = Campus coverage.
* **SAN** = Storage-focused.
* **SD-WAN** = Software-controlled WAN.
* **MPLS** = Label-based routing, prioritization.
* **mGRE** = Dynamic multipoint VPN tunnels.
* **Demarc** = ISP ↔ Customer boundary.
* **Smart Jack** = ISP diagnostic device.
* **DSL/Cable/Leased/Satellite/Metro** = Common ISP links.
* **vSwitch/vNIC/NFV/Hypervisor** = Virtual networking building blocks.

---
