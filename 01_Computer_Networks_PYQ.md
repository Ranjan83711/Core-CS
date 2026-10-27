# Bihar STET Paper 2 (Computer Science): Computer Networks PYQ Bank

**Papers covered (all official BSEB papers except 2024):**

| Year | Paper | CN questions found |
|---|---|---|
| 2019 | Second sitting (Set A); Set H has the same questions reshuffled | 21 |
| 2020 | Re-exam (Set B) | 18 |
| 2023 | 12 Sep 2023, Shift 1 | 13 |
| 2024 | 11 Jun 2024 (memory-based list from a coaching analysis, not the official paper) | 9 |
| 2025 | 3 Nov Shift 1 | 13 |
| 2025 | 3 Nov Shift 2 | 12 |
| 2025 | 4 Nov Shift 2 | 15 |
| 2025 | 7 Nov Shift 1 | 14 |
| **Total** | | **≈115 of ~800 CS questions (≈14%)** |

> Expect about **12–20 CN questions out of 100** in the CS section. That makes CN one of the highest-scoring topics.

**Notes on answers**
- Questions are rewritten in short form. Answers are the technically correct ones.
- Two official keys look wrong, so be careful:
  - In 2023, the key says ARP maps "MAC to IP". The correct answer is **IP → MAC**.
  - In 2023, the key says WSN = "Wireless Sensor Protocol". The correct answer is **Wireless Sensor Network**.

---

## 1. Topic frequency (where to focus)

| Rank | Topic | Times asked | Years |
|---|---|---|---|
| 1 | **Protocols & full forms** (HTTP/HTTPS, SMTP, FTP, SFTP, TCP, UDP, DHCP, ARP, SNMP, SSH, Telnet, VoIP, OSI) | ~25 | Every year |
| 2 | **Network security & cryptography** (firewall, SSL, symmetric/asymmetric, public/private key, MITM, CIA triad, threats) | ~15 | 2020, 2023–25 |
| 3 | **IP addressing** (IPv4/IPv6 size, valid IP, APIPA, header size, datagram size, subnetting, hierarchical addressing) | ~12 | 2019, 2020, 2025 ×4 |
| 4 | **Internet basics** (what the Internet is, ISP, DSL, IXP, ARPA, WWW, browser) | ~11 | 2019, 2020, 2025 |
| 5 | **Network devices** (router, repeater, gateway, switch/NIC, routing table) | ~8 | 2019, 2020, 2025 |
| 6 | **Transmission modes & media** (simplex/half/full duplex, optical fibre, Cat-5/6, bandwidth, parallel transmission) | ~8 | 2019, 2020, 2023, 2025 |
| 7 | **Data Link Layer** (MAC protocols, MAC address, framing, error control, parity, Hamming) | ~9 | 2019, 2023–25 |
| 8 | **Transport layer** (TCP vs UDP, port number, socket, process-to-process, TPDU, flow control, multiplexing) | ~9 | 2020, 2023–25 |
| 9 | **Network layer/routing** (routing, router function, routing table) | ~5 | 2020, 2023 |
| 10 | **Network types & topology** (topology, broadcast, overlay, nodes, distributed system) | ~6 | 2019, 2023, 2025 |
| 11 | **Multimedia networking** (jitter, RTSP, PCM, compression) | ~5 | 2020, 2023, 2025 |
| 12 | **Wireless/IoT networking** (BLE, WSN, ZigBee, MQTT, 3G/4G) | ~6 | 2023, 2025 |

---

## 2. Questions by topic (with answers)

### A. Protocols & full forms
| # | Asked (paraphrased) | Answer | Year |
|---|---|---|---|
| 1 | Full form of TCP in TCP/IP | Transmission Control Protocol | 2025 (3 Nov S1) |
| 2 | TCP/IP is a…? | Protocol (suite) | 2020 |
| 3 | Protocol used to send e-mail | **SMTP** | 2023, 2025 ×2 |
| 4 | Full form of HTTP | HyperText Transfer Protocol | 2024, 2025 (7 Nov) |
| 5 | Set of rules governing data transfer over the WWW | HTTP | 2025 (4 Nov) |
| 6 | What "S" in HTTPS stands for | Secure | 2025 (4 Nov) |
| 7 | What "https" in a web address indicates | Encrypted (SSL/TLS) connection | 2025 (3 Nov S2) |
| 8 | HTTP method to retrieve data from a server | **GET** | 2025 (7 Nov) |
| 9 | Full form of FTP | File Transfer Protocol | 2024, 2025 (4 Nov) |
| 10 | SFTP is used for | Secure file transfer (over SSH) | 2025 (3 Nov S2) |
| 11 | Protocol for secure remote login | **SSH** | 2025 (3 Nov S1) |
| 12 | Telnet is used for | Remote login/terminal access (insecure) | 2025 (4 Nov) |
| 13 | Connectionless protocol with minimal overhead | **UDP** | 2024, 2025 (4 Nov) |
| 14 | Purpose of ARP | Maps **IP address → MAC address** | 2023, 2025 (3 Nov S1) |
| 15 | Protocol that assigns IP addresses to clients | **DHCP** | 2019 |
| 16 | Primary function of SNMP | Network management and monitoring | 2024 |
| 17 | Protocol for phone calls over the Internet | **VoIP** (SIP/H.323) | 2025 (7 Nov) |
| 18 | Technology carrying voice as packets over an IP network | VoIP | 2025 (3 Nov S2) |
| 19 | Which is **not** an application-layer protocol? (RPC, IRC, RSVP) | **RSVP** (Resource Reservation Protocol) | 2019 |
| 20 | Which protocol is not used on the Internet? (HTTP, DHCP, DNS) | None of these (all are used) | 2019 |
| 21 | Agreement on how communication proceeds over a network | **Protocol** | 2020, 2025 (7 Nov) |
| 22 | Structure/format of data in a protocol | **Syntax** | 2019 |
| 23 | Full form of OSI | Open Systems Interconnection | 2020 |
| 24 | Number of OSI layers | **7** | 2025 (4 Nov) |
| 25 | IETF standards documents are called | **RFC** (Request for Comments) | 2020 |
| 26 | Real-time text communication service on the Internet | Instant messaging / chat (IRC) | 2025 (4 Nov) |
| 27 | Full form of SMS | Short Message Service | 2025 (4 Nov, 3 Nov S2 A-R) |
| 28 | Full form of MQTT | Message Queuing Telemetry Transport | 2025 (3 Nov S2) |

### B. Network security & cryptography
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | What a firewall is | System that prevents unauthorized access | 2020 |
| 2 | Communication-channel security protocol | **SSL** (TLS) | 2025 (7 Nov) |
| 3 | What SSL does | Creates a secure, encrypted connection to a web server (all of the above) | 2023, 2025 (7 Nov) |
| 4 | Private-key cryptography is also called | **Symmetric** | 2025 (3 Nov S1) |
| 5 | Encryption with a public key and a private key | **Asymmetric** (public-key) encryption | 2025 (4 Nov) |
| 6 | In public-key encryption, the key that encrypts / the key that decrypts | Public / Private | 2025 (7 Nov) |
| 7 | Study of encryption is called | Cryptography | 2024 |
| 8 | Which is not an encryption technique? | Know AES, DES, RSA, Blowfish as encryption algorithms | 2025 (3 Nov S2) |
| 9 | Attack that still works despite 2FA | **Man-in-the-middle** | 2025 (3 Nov S1) |
| 10 | "I" in the CIA triad | **Integrity** | 2025 (3 Nov S1) |
| 11 | Purpose of SQL injection | Bypass authentication / access the DB illegally | 2024, 2025 (4 Nov) |
| 12 | Which is not a physical threat? | **Hacking** (it is logical, not physical) | 2025 (4 Nov) |
| 13 | Which is not an external security threat? | **Underground threats** (front-door, back-door and DoS are external) | 2020 |
| 14 | Unsolicited e-mail is called | **Spam** | 2024 |
| 15 | Identify, implement and monitor security measures | Risk management | 2025 (3 Nov S1) |

### C. IP addressing
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Size of an IPv6 address | **128 bits** | 2019, 2025 (3 Nov S1) |
| 2 | IP version best for IoT | **IPv6** (huge address space) | 2025 (3 Nov S2) |
| 3 | Maximum size of an IPv4 datagram | **65,535 bytes** | 2025 (3 Nov S1) |
| 4 | Minimum IP header size | **20 bytes** | 2020 |
| 5 | Identify a valid IP address | Each octet must be 0–255 (e.g. 122.94.96.212 is valid) | 2025 (4 Nov) |
| 6 | APIPA address range | **169.254.0.1 – 169.254.255.254** | 2020 |
| 7 | Subnetting allows | Dividing a network into smaller sub-networks (efficient address use, less broadcast) | 2025 (7 Nov) |
| 8 | Hierarchical addressing at the network layer allows | Efficient/scalable routing (route aggregation) | 2025 (4 Nov) |

### D. Internet basics
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | What is the Internet? | A vast collection of different networks | 2019 |
| 2 | To join the Internet, connect to a… | **ISP** | 2019 |
| 3 | Internet over local telephone wires | **DSL** | 2019 |
| 4 | ISPs exchange traffic through | **Internet Exchange Point (IXP)** | 2019 |
| 5 | The Internet works on | **Packet switching** | 2019 |
| 6 | The Internet was originally a project of | **ARPA** (ARPANET) | 2020 |
| 7 | First web browser (as per key) | **Mosaic** (the first graphical browser to become popular) | 2025 (3 Nov S1) |
| 8 | "wwww" stands for | World Wide Web Worm | 2020 |
| 9 | Difference between a website and a web page | Website = a collection of web pages | 2025 (3 Nov S1) |
| 10 | URL vs web address | Same thing (URL = Uniform Resource Locator) | 2025 (4 Nov) |
| 11 | Main page of a website | Home page | 2020 |

### E. Network devices
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Device that forwards packets between networks using routing info | **Router** | 2019 |
| 2 | A router's routing table keeps | Routes for forwarding data to its destination | 2020 |
| 3 | Device that regenerates a weak signal | **Repeater** | 2025 (3 Nov S1) |
| 4 | Entry/exit point of a network | **Gateway** | 2025 (4 Nov) |
| 5 | Device that translates between protocols of different networks | **Gateway** | 2025 (7 Nov) |
| 6 | Device essential for a wired LAN | **Switch/Hub with NIC** (not a modem) | 2025 (3 Nov S2) |
| 7 | Which is not a network edge device? (PC, phone, server, switch) | **Switch** (a core/intermediate device) | 2019 |
| 8 | Hardware and software that let devices share information | Network | 2019 |

### F. Transmission modes & media
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Mobile phone call: mode | **Full duplex** | 2025 (3 Nov S1) |
| 2 | Keyboard → computer: mode | **Simplex** | 2019 |
| 3 | Mode used over a serial link | All (simplex, half and full duplex) | 2020 |
| 4 | Not a way of data exchange | **Multiplex** | 2020 |
| 5 | Data over multiple paths at the same time | Parallel transmission | 2023 |
| 6 | Medium with the highest speed | **Optical fibre** | 2019 |
| 7 | Cat-5/5E/6 are | **Twisted-pair** (UTP) cables | 2025 (7 Nov) |
| 8 | Maximum data a channel can carry per unit time | **Bandwidth** | 2025 (3 Nov S2) |
| 9 | Analog to digital bit stream | **PCM** (Pulse Code Modulation) | 2020 |

### G. Data Link Layer (MAC, framing, errors)
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Contention-based MAC protocols are used in | **Ethernet** (CSMA/CD) | 2023, 2025 (3 Nov S1) |
| 2 | Which is not used in media access control? | **DSL** | 2019 |
| 3 | True statements about MAC addresses | 48-bit (12 hex digits), burned into the NIC; not ISP-assigned and doesn't change with network | 2025 (4 Nov) |
| 4 | Frame design in the DLL includes | Defining the structure of frames | 2024 |
| 5 | Purpose of error control in the DLL | Detect and correct/retransmit erroneous frames | 2025 (3 Nov S2) |
| 6 | Main purpose of Data Link Control | Reliable node-to-node delivery (framing, flow and error control) | 2025 (7 Nov) |
| 7 | Parity check: how the receiver detects an error | Counts the 1s and checks against even/odd parity | 2025 (3 Nov S2) |
| 8 | Hamming code: parity-bit distance vs capability | Greater (minimum) distance means better detection/correction | 2023, 2025 (7 Nov) |

### H. Transport layer
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Port number in a TCP connection specifies | The communicating **process** on each end system | 2020 |
| 2 | Process-to-process communication is between | Processes on different devices (transport layer) | 2024, 2025 (3 Nov S2) |
| 3 | A socket is | A software endpoint for network communication (IP + port) | 2023, 2025 (3 Nov S2) |
| 4 | TPDU refers to | Data unit of the **transport layer** (segment) | 2025 (4 Nov) |
| 5 | TCP end-to-end flow control uses | **Window size advertisement** (sliding window) | 2024 |
| 6 | Managing data flow between nodes is called | **Flow control** | 2020 |
| 7 | Upward multiplexing | Many transport connections share one network connection | 2025 (7 Nov) |

### I. Network layer & routing
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Primary function of routing | Finding the best path for data | 2023 ×2 |
| 2 | Routing table holds | Routes to destinations | 2020 |

### J. Network types, topology & basics
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Term for how devices are interconnected | **Topology** | 2025 (7 Nov) |
| 2 | Which is NOT a topology? | Disk (bus, star, ring and mesh are topologies) | 2023 |
| 3 | Network built on top of another network | **Overlay network** | 2019 |
| 4 | Computers that appear as one coherent system | **Distributed system** | 2019 |
| 5 | Channel shared by all machines | **Broadcast network** | 2019 |
| 6 | Nodes in a network are | All: originating, routing and terminating computers | 2019 |
| 7 | Two devices are "in a network" if | A process on one can exchange information with a process on the other | 2019, 2020 |
| 8 | A computer network is | Hardware + communication channels + resource sharing (all) | 2020 |

### K. Multimedia networking
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Delay variation during stream playback | **Jitter** | 2023 |
| 2 | Jitter is caused by delay between | Packets | 2023 |
| 3 | RTSP teardown state | Server breaks down the connection | 2023 |
| 4 | Voice sampled at 8000 samples/s uses | 8 bits per sample (64 kbps) | 2023 |
| 5 | Purpose of compression in communication | Reduce data size, saving bandwidth and time | 2025 (4 Nov) |

### L. Wireless / IoT networking (overlaps with the IoT unit)
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | BLE stands for | Bluetooth Low Energy | 2023, 2024 |
| 2 | WSN stands for | Wireless Sensor Network | 2023, 2025 |
| 3 | "G" in 3G/4G/2G | Generation | 2020, 2025 |
| 4 | ZigBee device that relays data between devices | **ZigBee Router** | 2025 (3 Nov S1) |
| 5 | ZigBee is a task group of | IEEE 802.15.4 | 2025 (4 Nov) |

---

## 3. Must-revise checklist (from repeat patterns)

1. **Full forms**: TCP, UDP, IP, HTTP(S), FTP, SFTP, SMTP, POP3, IMAP, DNS, DHCP, ARP, RARP, SNMP, SSH, SSL/TLS, VoIP, OSI, ISP, DSL, IXP, LAN/MAN/WAN, NIC, MAC, URL, WWW, RFC, IETF, MQTT, BLE, WSN, PCM, TPDU.
2. **Port numbers**: HTTP 80, HTTPS 443, FTP 20/21, SSH 22, Telnet 23, SMTP 25, DNS 53, DHCP 67/68, POP3 110, IMAP 143, SNMP 161.
3. **OSI 7 layers ↔ TCP/IP 4 layers**: which protocol and data unit sit at each layer (bit → frame → packet → segment/TPDU → data).
4. **Devices by layer**: repeater/hub (L1), switch/bridge (L2), router (L3), gateway (all layers).
5. **IPv4 vs IPv6**: 32 vs 128 bits, IPv4 header 20–60 bytes, max datagram 65,535 bytes, classes A–E, private ranges, APIPA 169.254.x.x, loopback 127.0.0.1.
6. **Subnetting basics**: subnet mask, CIDR, hosts = 2ⁿ − 2.
7. **TCP vs UDP**: connection-oriented vs connectionless, flow control (sliding window), 3-way handshake.
8. **Transmission modes**: simplex, half and full duplex, with real examples (keyboard, walkie-talkie, phone).
9. **Media**: twisted pair (Cat-5/6), coaxial, optical fibre (fastest), and wireless (radio/microwave/infrared).
10. **Data Link Layer**: framing, parity, CRC, Hamming distance, CSMA/CD (Ethernet) vs CSMA/CA (Wi-Fi), MAC address (48-bit).
11. **Security**: firewall, symmetric vs asymmetric, public/private key roles, SSL/TLS, CIA triad, MITM, DoS, phishing, spam, SQL injection.
12. **Internet history**: ARPANET, Mosaic, Tim Berners-Lee (WWW), packet switching.

---

## 4. Sources

- Official papers (2019, 2020, 2023, 2025) from the [Adda247 PYQ page](https://www.adda247.com/teaching-jobs-exam/bihar-tet-previous-year-paper-2/) and the [Career Power PYQ page](https://www.careerpower.in/blog/bihar-stet-previous-year-question-papers)
- The 2024 list comes from the "Complete Bihar STET Paper II Analysis, Computer Science, 11 June 2024" PDF on Career Power. It is memory-based.
