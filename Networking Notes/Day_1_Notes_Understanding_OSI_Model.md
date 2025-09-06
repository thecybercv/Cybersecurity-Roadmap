📒 Day 1 – Understanding the OSI Model
🌐 OSI Model Overview

Full Form: Open System Interconnection Reference Model

Provides a common language to describe how data travels from start to end.

Each layer has unique protocols and specific responsibilities.

📝 Layers of OSI Model
🧠 Trick to Remember Sequence

“All People Seem To Need Data Processing”

All → Application Layer

People → Presentation Layer

Seem → Session Layer

To → Transport Layer

Need → Network Layer

Data → Data Link Layer

Processing → Physical Layer

1️⃣ Physical Layer

Deals with signaling, cables, connectors, fiber optics.

Common Problems & Fixes:

Fix cabling

Check punch-down connectors (push wire into special connector)

Run loopback test

Test/replace cables

Swap adapter cards

2️⃣ Data Link Layer

Foundational layer for higher protocols.

DLC Protocols → Example: Ethernet (uses MAC addresses)

Sometimes referred to as the switching layer.

3️⃣ Network Layer

Known as the routing layer.

Associated with IP addressing.

Frames can be fragmented/broken into smaller pieces.

4️⃣ Transport Layer

Referred to as the post-office layer.

Defines how data is delivered and where it goes.

Protocols: TCP & UDP

Example: A web page (e.g., Google) can’t be sent in one piece, so it is split into multiple segments.

5️⃣ Session Layer

Designed to start and stop communication.

Uses control and tunneling protocols.

Example: Device → “Can we talk?” → Google → Session setup begins.

6️⃣ Presentation Layer

Ensures proper data translation, encryption, and encoding.

Functions:

SSL/TLS

Character Encoding

Application Encryption

Often combined with Application Layer.

7️⃣ Application Layer

Closest to the end-user.

Example: Google homepage seen in browser.

Common Protocols: HTTP/HTTPS, FTP, DNS, POP3

🔎 Practical Real-World Example (Wireshark)

Frame 88 (Bytes received) → Physical Layer

Ethernet II (MAC Address) → Data Link Layer

Internet Protocol (IP Address) → Network Layer

TCP (Source Port → Destination Port) → Transport Layer

SSL/TLS (Session + Presentation + Application)

📊 Example OSI Mapping
OSI Layer	Example
Application	https://mail.google.com
Presentation	SSL Encryption
Session	Links presentation to transport
Transport	TCP encapsulation
Network	IP encapsulation
Data Link	Ethernet
Physical	Electrical signals
