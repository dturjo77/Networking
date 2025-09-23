# OSI Model:

## Introduction to OSI Model
The OSI (Open Systems Interconnection) model is a framework for understanding how networks work. It was created by ISO in the late 1970s to allow different vendors' devices to communicate. It divides network communication into 7 layers, from physical hardware to user applications.

- **Purpose**: Makes networks interoperable, easier to design, troubleshoot, and standardize.
- **Not Physical**: It's a conceptual model, not actual hardware.

## The Layered Approach
Think of the OSI model like departments in a company:
- Each layer has specific tasks.
- Layers communicate with the same layer on other devices (peer-to-peer).
- Upper layers (1-3) handle applications and user interaction.
- Lower layers (4-7) handle data transmission.

This "binding" means developers focus on one layer without worrying about others.

## Advantages of Reference Models
- Breaks complex processes into simple layers for easier development and troubleshooting.
- Allows multi-vendor compatibility through standards.
- Encourages industry-wide standardization.
- Enables different hardware/software to communicate.
- Changes in one layer don't affect others, making updates easier.

## The OSI Reference Model
The OSI has 7 layers:
1. **Application (Layer 7)**: User interface for apps like email, file transfer (e.g., HTTP, FTP). Handles resource availability and partner communication.
2. **Presentation (Layer 6)**: Translates data formats (e.g., ASCII to EBCDIC), compression, encryption. Ensures data is readable between systems.
3. **Session (Layer 5)**: Manages sessions/dialogs between apps. Controls simplex/half-duplex/full-duplex modes. Keeps app data separate.
4. **Transport (Layer 4)**: End-to-end delivery. Segments data, handles reliability (TCP) or speed (UDP). Includes flow control, error correction, windowing.
5. **Network (Layer 3)**: Logical addressing (IP), routing packets between networks. Routers operate here. Breaks broadcast domains.
6. **Data Link (Layer 2)**: Frames data for local delivery using MAC addresses. Handles error detection (not correction). Switches operate here. Sublayers: MAC (media access) and LLC (protocol identification).
7. **Physical (Layer 1)**: Transmits raw bits over media (cables, wireless). Defines voltages, connectors, topologies (bus, star, etc.).

**Upper Layers (5-7)**: Application-focused, user interaction.
**Lower Layers (1-4)**: Data transmission, hardware-focused.

## The Application Layer
- Where users interact with the network (e.g., browsers, email clients).
- Manages app services like file/print/database.
- Checks partner availability and resources.
- Interfaces with OS via APIs; not the app itself.

## The Presentation Layer
- Formats data for compatibility (e.g., encryption, compression).
- Converts between formats like EBCDIC/ASCII.
- Handles multimedia standards.

## The Session Layer
- Sets up, manages, ends sessions.
- Controls dialog (simplex, half/full-duplex).
- Keeps multiple app sessions separate (e.g., multiple browser tabs).

## The Transport Layer
- Segments/reassembles data.
- Provides end-to-end connection: Reliable (TCP: acknowledgments, sequencing, flow control) or unreliable (UDP: fast, no checks).
- **Connection-Oriented**: 3-way handshake (SYN, SYN/ACK, ACK), virtual circuits.
- **Flow Control**: Prevents buffer overflow using "not ready" signals.
- **Windowing**: Sends multiple segments before ACK (e.g., window size 3).
- **Acknowledgments**: Ensures delivery; retransmits lost segments.

## The Network Layer
- Logical addressing (IP) and routing.
- Routers forward packets based on destination network.
- Packets: Data (user info) or route-updates (RIP, OSPF).
- Breaks broadcast domains; provides QoS.
- Key: Routers don't forward broadcasts/multicasts by default.

## The Data Link Layer
- Frames packets with MAC addresses for local delivery.
- Error detection (CRC), flow control.
- Sublayers: MAC (access media, topologies) and LLC (encapsulate protocols).
- Switches/bridges operate here; breaks collision domains.

## The Physical Layer
- Transmits bits (1s/0s) over media.
- Defines cables, voltages, pinouts, topologies (bus, star).
- Interfaces: DTE (device) and DCE (modem/CSU/DSU).
- No intelligence; just raw signal transmission.

## Introduction to Encapsulation
Data travels down the OSI stack, getting wrapped (encapsulated) at each layer:
1. User data → Segments (Transport).
2. Segments → Packets (Network, adds IP).
3. Packets → Frames (Data Link, adds MAC).
4. Frames → Bits (Physical).

At receiver: Reverse process (decapsulation). Packet unchanged; only headers/footers added/removed per hop.

## Modulation Techniques
- Varies signal properties to transmit data.
- **Modulation**: Encodes digital/analog signals into carrier waves.
- **Types**:
  - Digital: Line coding for baseband (full bandwidth).
  - Analog: For passband (filtered frequencies).
- **Multiplexing**:
  - FDM: Multiple signals on different frequencies.
  - TDM: Time-sharing signals.
- Devices: Modems (modulate/demodulate).

**Mnemonic for Layers**: Please Do Not Throw Sausage Pizza Away (Physical → Application).

This note is simplified for quick reference. Store as `OSI_Model_Notes.md` in GitHub for easy access and versioning!
