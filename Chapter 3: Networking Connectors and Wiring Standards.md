Chapter 3: Networking Connectors and Wiring Standards
This chapter explains the cables, connectors, and wiring standards used to build computer networks. Whether you're setting up a home Wi-Fi or a large office network, understanding physical media (cables) and how they're connected is key. Even wireless networks need wired backbones to work. We'll cover the main types of cables, their properties, how to connect them, and the equipment used to organize them.
1. Introduction to Physical Media
Networks rely on physical media to carry data signals. These can be cables (like copper or fiber) or even the air for wireless signals. Most local networks (LANs) use cables, while wireless networks connect to wired backbones (like fiber to Wi-Fi routers). The main cable types are:

Coaxial: Thick cables used for cable TV or old networks.
Twisted-Pair: Common for modern office and home networks.
Fiber-Optic: High-speed cables for long distances or data centers.
Twinaxial: For short, fast connections in data centers.

Each cable has unique features that make it best for specific uses, like speed or distance.
2. Cable Properties
Cables differ in five key properties: speed, distance, duplex, noise immunity, and frequency. These determine which cable to use for a network.
2.1 Transmission Speeds

Definition: How fast data travels, measured in Mbps (megabits per second) or Gbps (gigabits per second).
Core Networks: Need high speeds (10 Gbps+) to connect network segments (like building backbones).
User Areas: Need 100 Mbps–10 Gbps for devices like computers or phones.
Examples:
Twisted-Pair (Cat 5e): 1 Gbps.
Twisted-Pair (Cat 6A): 10 Gbps.
Fiber-Optic: 100 Gbps or more.



2.2 Distance

Definition: How far a signal can travel before it weakens (called attenuation).
Limits:
Twisted-Pair: Up to 100 meters (328 feet).
Coaxial: 185–500 meters (older networks).
Fiber-Optic: 550 meters to 100 kilometers.


Why It Matters: Longer distances need repeaters (to boost signals) or fiber for best performance.

2.3 Duplex

Half-Duplex: Devices take turns sending or receiving (like a walkie-talkie). Example: Old network hubs.
Full-Duplex: Devices send and receive at the same time (like a phone call). Doubles speed. Used in modern switches.
Why It Matters: Full-duplex needs all cable wires (e.g., 4 pairs for Gigabit Ethernet).

2.4 Noise Immunity (Security and EMI)

Electromagnetic Interference (EMI): Copper cables create magnetic fields that can be tapped (security risk) or pick up noise from motors, lights, or other devices.
Copper Solutions:
Use Shielded Twisted-Pair (STP) for better EMI protection.
Keep cables away from EMI sources like fluorescent lights.


Fiber-Optic: Uses light, not electricity, so it's immune to EMI and harder to tap (more secure).
Example: Use fiber near elevators or in secure networks like banks.

2.5 Frequency

Definition: How fast a cable can carry signals, measured in MHz (megahertz) or GHz (gigahertz). Higher frequency = more data.
Examples:
Cat 5e: 100 MHz (1 Gbps).
Cat 6: 250 MHz (1–10 Gbps).
Cat 8: 2 GHz (25–40 Gbps).
Fiber: Terahertz (100 Gbps+).


Why It Matters: Higher frequency cables have more twists or better materials for faster speeds.

3. Coaxial Cable
3.1 What Is It?
A thick cable with a copper core, a shield (to block EMI), and a plastic jacket. Used in old networks and modern cable TV or internet.
3.2 Types

Thinnet (10Base2): Thin (5mm), 10 Mbps, 185m range. Uses RG-58 cable.
Thicknet (10Base5): Thicker (10mm), 10 Mbps, 500m range.
Modern: RG-6/RG-59 for cable TV or broadband (up to 1 Gbps).

3.3 Connectors

BNC: For thinnet, crimped or screwed on. Needs 50-ohm terminators at cable ends.
F-Type: Screw-on for cable TV or RG-6.
Couplers: Join cable segments.

3.4 Plenum vs. Non-Plenum

Plenum-Rated: Fire-safe, low smoke, used in air spaces (e.g., ceilings). Often made with Teflon (FEP). Required by fire codes.
Non-Plenum: Cheaper (PVC), but releases toxic smoke in fires. Use only in safe areas.

3.5 Uses

Old Ethernet networks (1980s–1990s).
Today: Cable TV, broadband, security cameras.

3.6 Pros and Cons

Pros: Good EMI resistance, longer range than early twisted-pair.
Cons: Bulky, hard to install, mostly obsolete for LANs.

4. Twisted-Pair Cable
4.1 What Is It?
Copper wires twisted in pairs (4 pairs, 8 wires) to reduce interference (crosstalk and EMI). Most common for home and office networks.
4.2 Types

Unshielded Twisted-Pair (UTP): No extra shield, relies on twisting. Cheap and flexible.
Shielded Twisted-Pair (STP): Has a foil or braided shield for EMI-heavy areas (e.g., factories).
Foiled Twisted-Pair (FTP): Foil around all pairs, less common.

4.3 Categories
Categories define speed and frequency. Higher numbers = faster, more twists.



Category
Frequency
Speed/Distance
Use
Status



Cat 1
1 MHz
Voice only (phones)
Old phones
Obsolete


Cat 2
10 MHz
4 Mbps
Early data
Obsolete


Cat 3
16 MHz
10 Mbps
Old Ethernet
Obsolete


Cat 4
20 MHz
16 Mbps
Token Ring
Obsolete


Cat 5
100 MHz
100 Mbps
Fast Ethernet
Rare


Cat 5e
100 MHz
1 Gbps/100m
Gigabit LANs
Standard


Cat 6
250 MHz
1–10 Gbps/55m
Backbones
Common


Cat 6A
500 MHz
10 Gbps/100m
High-speed LANs
For 10G


Cat 7
600 MHz
10 Gbps/100m
Data centers
Less common


Cat 8
2 GHz
25–40 Gbps/30m
Data centers
Emerging


4.4 Ethernet Standards

10BaseT: 10 Mbps (Cat 3+).
100BaseTX: 100 Mbps (Cat 5+, 2 pairs).
1000BaseT: 1 Gbps (Cat 5e+, 4 pairs).
10GBaseT: 10 Gbps (Cat 6A+).

4.5 Twinaxial (Twinax)

Two copper conductors in a shielded jacket.
Used for short (up to 30m), high-speed (10–400 Gbps) data center links.
Cheaper than fiber but copper-based.

4.6 Connectors

RJ-45: 8-pin for networks, crimped onto cable.
RJ-11: 4-6 pins for phones, not for LANs.
RJ-48C: Like RJ-45, but for T1 WAN links (shielded, different wiring).

4.7 Pros and Cons

Pros: Cheap ($0.10–$0.50/m), easy to install, supports 100 Mbps–40 Gbps.
Cons: Limited to 100m, EMI issues (UTP), less secure than fiber.

4.8 Installation Tips

Don’t stretch cables (reduces twists, lowers speed).
Use all 4 pairs for Gigabit+.
Match category (e.g., Cat 6 cable, jacks, panels).
Test with cable testers for wiring and crosstalk.

5. Fiber-Optic Cable
5.1 What Is It?
Transmits data as light through a glass or plastic core. Immune to EMI, used for high-speed or long-distance networks.
5.2 Structure

Core: Carries light (glass or plastic).
Cladding: Reflects light back into core.
Buffer: Protects core.
Strength Member: Kevlar for durability.
Jacket: PVC or plenum-rated.

5.3 Types

Single-Mode Fiber (SMF):
Thin core (8–10µm), one light path.
Laser light source, up to 100km, 10–400 Gbps.
Used for telecom, WANs, campus links.


Multimode Fiber (MMF):
Thicker core (50–62.5µm), multiple light paths.
LED light source, up to 550–900m, up to 100 Gbps.
Used for LANs, data centers.
Plastic MMF: Easier to install, shorter range.



5.4 Connectors

Standard:
ST (Straight Tip): Twist-lock, for LANs.
SC (Subscriber Connector): Push-pull, durable, telecom.
FC (Ferrule Connector): Screw-on, high-precision, telecom.


Small Form Factor (SFF):
MT-RJ: Compact, early Gigabit Ethernet.
LC (Local Connector): Small, high-density, data centers.


APC vs. UPC:
UPC (Ultra Physical Contact): Flat end, more signal loss (~–50 dB).
APC (Angled Physical Contact): 8° angle, less loss (~–60 dB), for high-performance.



5.5 Transceivers

Combine transmitter and receiver to connect fiber to devices.
Types:
SFP/SFP+: 10–16 Gbps, for switches/routers.
QSFP/QSFP28: 40–100 Gbps, for high-speed links.


Modes: Simplex (one-way), Duplex (two-way), WDM (two-way on one fiber).

5.6 Media Converters

Convert signals between media:
SMF/MMF to Ethernet.
Fiber to coaxial.
SMF to MMF.


Used to connect different network segments.

5.7 Pros and Cons

Pros: High speed (100 Gbps+), long distance (up to 100km), secure, EMI-immune.
Cons: Expensive ($1–$10/m), fragile, hard to install, costly testing tools.

5.8 Installation Tips

Avoid tight bends (<10x cable diameter).
Clean connectors to prevent signal loss.
Use OTDR testers for loss or breaks.
Use plenum-rated cables in air spaces.
Never look into live fiber (laser risk).

6. Wiring Standards
6.1 Why Standards?
Ensure consistent wiring to avoid errors and support high speeds. Define how wires connect to RJ-45 pins.
6.2 T568A vs. T568B

T568A: White/Green (1), Green (2), White/Orange (3), Blue (4), White/Blue (5), Orange (6), White/Brown (7), Brown (8).
T568B: White/Orange (1), Orange (2), White/Green (3), Blue (4), White/Blue (5), Green (6), White/Brown (7), Brown (8).
Difference: Swaps orange/green pairs (pins 1,2 vs. 3,6).
Use: T568B is standard in the U.S.; pick one and stick to it.

6.3 Cable Types

Straight-Through:
Connects different devices (e.g., PC to switch).
Same pinout both ends (T568B-to-T568B).
Uses pins 1,2,3,6 for 10/100 Mbps; all 8 for Gigabit+.


Crossover:
Connects similar devices (e.g., switch-to-switch, PC-to-PC).
T568A-to-T568B (swaps 1-to-3, 2-to-6).
Modern switches auto-adjust (MDI-X), reducing need.


Rolled/Rollover:
For console connections (PC to router/switch serial port).
Flips all pins (1-to-8, 2-to-7).
Uses RJ-45 to DB-9/USB for configuration.


T1 Crossover:
For T1 WAN links (CSU/DSU to CSU/DSU).
Swaps pins 1,2 to 4,5.



6.4 Testing

Use cable testers to check wiring, continuity, and crosstalk.
Ensure correct cable type (straight/crossover) for the connection.

7. Wiring Distribution Components
7.1 Purpose
Organize cables in buildings for reliable, scalable networks.
7.2 Components

Main Distribution Frame (MDF):
Central hub, often at WAN entry (demarc).
Connects internal cables to provider lines (e.g., internet, phone).


Intermediate Distribution Frame (IDF):
Secondary hub in equipment rooms, linked to MDF.
Distributes cables to floors or areas.


25-Pair Cable:
Bundles 25 wire pairs for phone backbones.
Not used for modern data networks.


66 Block:
Old punch-down block (1962) for analog phones.
Uses 25-pair cables, obsolete for data.


110 Block:
Modern punch-down for phone (RJ-11) or network (RJ-45).
Supports 1 Gbps with Cat 6; harder with Cat 6+.
Variant: Krone block (European).


BIX Block:
Punch-down for 25 pairs, no pre-stripping needed.
Less common than 110.


Demarc (Demarcation Point):
Where provider’s responsibility ends (usually RJ-45 jack).
Test both sides to find network issues.


Demarc Extension: Cable from demarc to office equipment.
Smart Jack (NID/NIU):
Provider device at demarc for testing and signal conversion.
Connects to routers or CSU/DSU.



8. Serial Cables and Legacy Connectors
8.1 What Are They?
Serial cables send one bit at a time (unlike parallel cables for old printers).
8.2 Types

RS-232:
Old standard for modems, serial ports.
Uses DB-9 or DB-25 connectors, up to 115 Kbps.
Obsolete, replaced by USB.


DB-25/DB-9:
DB-25: 25-pin for RS-232.
DB-9: 9-pin for Cisco console cables, now USB.


Universal Serial Bus (USB):
Modern serial standard for printers, keyboards, etc.
Supports 127 devices via hubs.
Speeds: 480 Mbps (USB 2.0) to 20 Gbps (USB 4.0).
Types: USB-A, USB-C (for modern consoles).



9. Installation Best Practices

Cable Handling:
Twisted-Pair: Don’t stretch (hurts twists).
Fiber: Avoid tight bends, clean connectors.
Copper: Keep away from EMI (motors, lights).


Standards: Follow TIA/EIA-568 (use T568B in U.S.).
Matching Components: Use same category (e.g., Cat 6 cable, jacks, panels).
Testing:
Twisted-Pair: Cable testers for wiring, crosstalk.
Fiber: OTDR for loss, breaks.


Safety:
Use plenum-rated cables in ceilings (fire safety).
Fiber: Don’t look into live cables (laser danger).


Labeling: Mark cables/ports for easy fixes.
Certification: Use tools like Fluke to verify performance.

10. Applications and Future Trends
10.1 Applications

Coaxial: Cable TV, broadband (RG-6/59).
Twisted-Pair: Office/home LANs, Power over Ethernet (Cat 5e+).
Fiber: Data centers, internet backbones, fiber-to-the-home (FTTH).
Twinax: Short, high-speed data center links.

10.2 Future Trends

Twisted-Pair: Cat 8 for 25–40 Gbps; 2.5/5GBaseT over Cat 5e/6.
Fiber: 400 Gbps+ for cloud computing and telecom.
Wireless: More wired backbones (fiber) for 5G/6G.

10.3 Choosing Cables

Copper (Twisted-Pair/Twinax): For short runs (<100m), low cost.
Fiber: For long distances, high speeds, or secure/noisy areas.
Coaxial: For specific uses like broadband.

11. Quick Reference Table



Cable Type
Speed
Distance
EMI Immunity
Common Use



Coaxial
Up to 1 Gbps
185–500m
Good (shielded)
Broadband, TV


Twisted-Pair
100 Mbps–40 Gbps
100m
Moderate (UTP); Good (STP)
LANs, PoE


Fiber-Optic
10–400 Gbps+
550m–100km
Excellent (immune)
Backbones, data centers


Twinax
10–400 Gbps
30m
Good (shielded)
Data centers


12. Tips for Beginners

Learn Wiring: Practice crimping RJ-45 for straight-through/crossover cables.
Use Testers: Check cables with testers to avoid wiring mistakes.
Follow Standards: Stick to T568B for consistency.
Safety First: Use plenum cables in ceilings; be careful with fiber.
Study More: Look up TIA/EIA-568 standards or take a networking course (e.g., CompTIA Network+).

This chapter gives you the basics to understand and work with network cables and connectors. For real-world setups, hire certified installers for complex projects and always check local fire codes.
