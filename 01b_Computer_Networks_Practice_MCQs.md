# Computer Networks: Practice MCQs (240 questions)

**Bihar STET Paper 2 (Computer Science)**

There are 12 topics with 20 questions each. They follow the topic list in `01_Computer_Networks_PYQ.md`.

**How to use**
- The answer is shown right under each question, so you can revise in one read.
- Aim for 17/20 or better in every topic before the exam.
- Re-read the topic in the PYQ file wherever you score lower.

---

## A. Protocols & Full Forms

**1.** What is the default port of HTTPS?
(A) 80  (B) 443  (C) 21  (D) 25

✅ **Ans: (B) 443** — HTTP = 80, HTTPS = 443

**2.** POP3 is used to:
(A) send e-mail  (B) retrieve e-mail from a mail server  (C) transfer files  (D) resolve domain names

✅ **Ans: (B) retrieve e-mail from a mail server** — POP3 (port 110) downloads mail. SMTP sends it.

**3.** Which protocol translates domain names into IP addresses?
(A) DHCP  (B) ARP  (C) DNS  (D) SNMP

✅ **Ans: (C) DNS** — DNS (port 53)

**4.** FTP uses which port numbers?
(A) 20 and 21  (B) 22 and 23  (C) 25 and 110  (D) 53 and 67

✅ **Ans: (A) 20 and 21** — 20 = data, 21 = control

**5.** What is the default port of SMTP?
(A) 110  (B) 143  (C) 25  (D) 53

✅ **Ans: (C) 25**

**6.** Which of these is a connection-oriented protocol?
(A) UDP  (B) IP  (C) TCP  (D) ICMP

✅ **Ans: (C) TCP** — UDP is connectionless

**7.** Which protocol does the `ping` command use?
(A) ICMP  (B) IGMP  (C) ARP  (D) UDP

✅ **Ans: (A) ICMP** — Echo request/reply

**8.** RARP is used to:
(A) find the MAC address from an IP address  (B) find the IP address from a MAC address  (C) assign port numbers  (D) encrypt packets

✅ **Ans: (B) find the IP address from a MAC address** — ARP: IP → MAC. RARP: MAC → IP.

**9.** IMAP stands for:
(A) Internet Message Access Protocol  (B) Internal Mail Access Protocol  (C) Internet Mail Address Protocol  (D) Interactive Message Access Protocol

✅ **Ans: (A) Internet Message Access Protocol** — Port 143

**10.** Which of these works at the application layer?
(A) IP  (B) TCP  (C) HTTP  (D) Ethernet

✅ **Ans: (C) HTTP**

**11.** What is the default port of SSH?
(A) 21  (B) 22  (C) 23  (D) 80

✅ **Ans: (B) 22** — Telnet = 23

**12.** Telnet is considered insecure because:
(A) it runs over UDP  (B) it sends data, including passwords, as plain text  (C) it uses port 22  (D) it has no login step

✅ **Ans: (B) it sends data, including passwords, as plain text** — SSH replaced it

**13.** A DHCP server normally gives a client:
(A) only an IP address  (B) an IP address, subnet mask, default gateway and DNS server  (C) a MAC address  (D) only a domain name

✅ **Ans: (B) an IP address, subnet mask, default gateway and DNS server**

**14.** SNMP is used for:
(A) e-mail  (B) file transfer  (C) network management and monitoring  (D) web browsing

✅ **Ans: (C) network management and monitoring** — Port 161

**15.** Which protocol transfers web pages from a server to a browser?
(A) HTTP  (B) SMTP  (C) FTP  (D) SNMP

✅ **Ans: (A) HTTP**

**16.** In a protocol, "semantics" refers to:
(A) the format of the data  (B) the meaning of each section of bits  (C) when data is sent  (D) the speed of data

✅ **Ans: (B) the meaning of each section of bits** — Syntax = format. Timing = when.

**17.** Which HTTP method sends form data to the server to create or submit something?
(A) GET  (B) POST  (C) HEAD  (D) TRACE

✅ **Ans: (B) POST** — GET retrieves data

**18.** What does HTTP status code 404 mean?
(A) OK  (B) Internal server error  (C) Not Found  (D) Moved permanently

✅ **Ans: (C) Not Found** — 200 OK, 500 server error, 301 moved

**19.** Which of these is a stateless protocol?
(A) HTTP  (B) TCP  (C) FTP  (D) SSH

✅ **Ans: (A) HTTP** — Each request is independent (cookies/sessions add state)

**20.** Which signalling protocol is commonly used to set up VoIP calls?
(A) SIP  (B) SMTP  (C) POP3  (D) ARP

✅ **Ans: (A) SIP** — Session Initiation Protocol

---

## B. Network Security & Cryptography

**1.** A firewall protects a network by:
(A) filtering traffic according to rules  (B) speeding up traffic  (C) assigning IP addresses  (D) storing backups

✅ **Ans: (A) filtering traffic according to rules** — Packet filtering, stateful inspection, proxy

**2.** In symmetric encryption:
(A) two different keys are used  (B) no key is used  (C) the same key is used to encrypt and decrypt  (D) only a public key is used

✅ **Ans: (C) the same key is used to encrypt and decrypt** — Also called private-key / secret-key cryptography

**3.** RSA is an example of:
(A) symmetric encryption  (B) hashing  (C) steganography  (D) asymmetric encryption

✅ **Ans: (D) asymmetric encryption** — Rivest–Shamir–Adleman

**4.** AES is:
(A) an asymmetric algorithm  (B) a hash function  (C) a symmetric block cipher  (D) a mail protocol

✅ **Ans: (C) a symmetric block cipher** — DES and 3DES are also symmetric

**5.** In the CIA triad, "A" stands for:
(A) Authentication  (B) Authorization  (C) Availability  (D) Accountability

✅ **Ans: (C) Availability** — Confidentiality, Integrity, Availability

**6.** To send a confidential message to Ravi using public-key cryptography, the sender encrypts it with:
(A) the sender's private key  (B) Ravi's public key  (C) Ravi's private key  (D) the sender's public key

✅ **Ans: (B) Ravi's public key** — Only Ravi's private key can decrypt it

**7.** A digital signature is created using:
(A) the sender's private key  (B) the receiver's public key  (C) the receiver's private key  (D) a shared secret key

✅ **Ans: (A) the sender's private key** — Verified with the sender's public key

**8.** A Denial-of-Service (DoS) attack mainly affects:
(A) Confidentiality  (B) Integrity  (C) Availability  (D) Authentication

✅ **Ans: (C) Availability**

**9.** Phishing means:
(A) using fake e-mails or websites to steal sensitive information  (B) a self-replicating virus  (C) physically stealing a computer  (D) flooding a server with requests

✅ **Ans: (A) using fake e-mails or websites to steal sensitive information**

**10.** Which malicious program spreads across a network by itself, without attaching to a host file?
(A) Virus  (B) Trojan horse  (C) Spyware  (D) Worm

✅ **Ans: (D) Worm** — A virus needs a host file

**11.** Malware disguised as useful software is called:
(A) a Worm  (B) a Trojan horse  (C) Adware  (D) a Cookie

✅ **Ans: (B) a Trojan horse**

**12.** SSL/TLS works between which layers?
(A) Physical and Data Link  (B) Network and Data Link  (C) Transport and Application  (D) None of these

✅ **Ans: (C) Transport and Application** — HTTPS = HTTP over TLS

**13.** Converting ciphertext back into plaintext is called:
(A) Decryption  (B) Encryption  (C) Hashing  (D) Encoding

✅ **Ans: (A) Decryption**

**14.** MD5 and SHA-256 are:
(A) encryption algorithms  (B) key-exchange protocols  (C) firewalls  (D) hash functions

✅ **Ans: (D) hash functions** — One-way functions, used for integrity

**15.** The Caesar cipher is a:
(A) transposition cipher  (B) substitution cipher  (C) public-key cipher  (D) hash function

✅ **Ans: (B) substitution cipher** — Each letter is shifted by a fixed number

**16.** An attacker secretly intercepts, and may change, the messages between two parties. This is a:
(A) Man-in-the-middle attack  (B) DoS attack  (C) Phishing attack  (D) Brute-force attack

✅ **Ans: (A) Man-in-the-middle attack** — 2FA does not stop MITM (PYQ 2025)

**17.** A DDoS attack is launched using:
(A) a single computer  (B) firewalls only  (C) many compromised computers (a botnet)  (D) encryption

✅ **Ans: (C) many compromised computers (a botnet)** — Distributed DoS

**18.** A VPN provides:
(A) free internet  (B) a faster CPU  (C) antivirus protection  (D) a secure, encrypted tunnel over a public network

✅ **Ans: (D) a secure, encrypted tunnel over a public network**

**19.** Which security goal ensures that a sender cannot deny having sent a message?
(A) Confidentiality  (B) Non-repudiation  (C) Availability  (D) Integrity

✅ **Ans: (B) Non-repudiation** — Achieved with digital signatures

**20.** The Diffie–Hellman algorithm is used for:
(A) key exchange  (B) hashing  (C) compression  (D) routing

✅ **Ans: (A) key exchange**

---

## C. IP Addressing

**1.** How long is an IPv4 address?
(A) 16 bits  (B) 32 bits  (C) 64 bits  (D) 128 bits

✅ **Ans: (B) 32 bits** — IPv6 = 128 bits

**2.** Which IP address is invalid?
(A) 192.168.1.1  (B) 10.0.0.255  (C) 256.10.1.1  (D) 172.16.5.4

✅ **Ans: (C) 256.10.1.1** — Each octet must be 0–255

**3.** What is the IPv4 loopback address?
(A) 127.0.0.1  (B) 0.0.0.0  (C) 255.255.255.255  (D) 192.168.0.1

✅ **Ans: (A) 127.0.0.1** — The whole 127.0.0.0/8 range is loopback

**4.** What is the first-octet range of a Class A address?
(A) 128–191  (B) 192–223  (C) 1–126  (D) 224–239

✅ **Ans: (C) 1–126** — 127 is reserved for loopback. B: 128–191, C: 192–223, D: 224–239, E: 240–255

**5.** What is the default subnet mask of a Class C network?
(A) 255.0.0.0  (B) 255.255.0.0  (C) 255.255.255.255  (D) 255.255.255.0

✅ **Ans: (D) 255.255.255.0** — A = /8, B = /16, C = /24

**6.** Class D addresses are used for:
(A) unicast  (B) multicast  (C) broadcast  (D) experimental use

✅ **Ans: (B) multicast** — Class E is experimental

**7.** Which of these is a private IP range?
(A) 10.0.0.0/8  (B) 11.0.0.0/8  (C) 128.0.0.0/8  (D) 200.0.0.0/8

✅ **Ans: (A) 10.0.0.0/8** — Private ranges: 10/8, 172.16–31/12, 192.168/16

**8.** How many usable host addresses does a /24 network have?
(A) 256  (B) 254  (C) 255  (D) 252

✅ **Ans: (B) 254** — 2⁸ − 2 (network and broadcast addresses excluded)

**9.** What is the subnet mask for /26?
(A) 255.255.255.128  (B) 255.255.255.224  (C) 255.255.255.192  (D) 255.255.255.240

✅ **Ans: (C) 255.255.255.192** — 26 one-bits: last octet = 11000000 = 192

**10.** How is an IPv6 address written?
(A) four decimal octets  (B) eight groups of four hex digits separated by colons  (C) six hex groups separated by hyphens  (D) pure binary

✅ **Ans: (B) eight groups of four hex digits separated by colons** — 8 × 16 bits = 128 bits

**11.** In an IPv6 address, "::" stands for:
(A) broadcast  (B) loopback only  (C) an error  (D) one or more consecutive groups of zeros

✅ **Ans: (D) one or more consecutive groups of zeros** — "::" may be used only once in an address

**12.** What is the IPv6 loopback address?
(A) ::1  (B) ::0  (C) FF::1  (D) 127::1

✅ **Ans: (A) ::1**

**13.** Which IPv4 feature does not exist in IPv6?
(A) Multicast  (B) Unicast  (C) Broadcast  (D) Anycast

✅ **Ans: (C) Broadcast** — IPv6 uses multicast/anycast instead

**14.** How many addresses can IPv6 provide in total?
(A) 2³²  (B) 2⁶⁴  (C) 2¹²⁸  (D) 2²⁵⁶

✅ **Ans: (C) 2¹²⁸**

**15.** What is the maximum size of an IPv4 header?
(A) 20 bytes  (B) 40 bytes  (C) 60 bytes  (D) 64 bytes

✅ **Ans: (C) 60 bytes** — Minimum 20 bytes (PYQ 2020)

**16.** The TTL field in the IPv4 header prevents:
(A) collisions  (B) packets looping forever  (C) fragmentation  (D) eavesdropping

✅ **Ans: (B) packets looping forever** — Decremented at every router

**17.** CIDR stands for:
(A) Classless Inter-Domain Routing  (B) Classful Internet Data Routing  (C) Common IP Domain Range  (D) Central Internet Distribution Routing

✅ **Ans: (A) Classless Inter-Domain Routing**

**18.** What is the broadcast address of 192.168.10.0/24?
(A) 192.168.10.0  (B) 192.168.10.1  (C) 192.168.255.255  (D) 192.168.10.255

✅ **Ans: (D) 192.168.10.255** — All host bits = 1

**19.** NAT is used to:
(A) assign MAC addresses  (B) translate private IP addresses to a public IP address  (C) encrypt packets  (D) resolve domain names

✅ **Ans: (B) translate private IP addresses to a public IP address** — Network Address Translation

**20.** A PC shows the IP address 169.254.12.7. This usually means:
(A) DHCP failed, so the PC gave itself an APIPA address  (B) it is a multicast address  (C) it is a loopback address  (D) it is a public internet address

✅ **Ans: (A) DHCP failed, so the PC gave itself an APIPA address** — APIPA range 169.254.0.1–169.254.255.254 (PYQ 2020)

---

## D. Internet Basics

**1.** ARPANET was funded by:
(A) the US Department of Defense  (B) IBM  (C) Microsoft  (D) CERN

✅ **Ans: (A) the US Department of Defense** — Through ARPA (later DARPA), 1969

**2.** The World Wide Web was invented by:
(A) Vint Cerf  (B) Tim Berners-Lee  (C) Bill Gates  (D) Charles Babbage

✅ **Ans: (B) Tim Berners-Lee** — 1989, at CERN

**3.** Who is called the "Father of the Internet" for co-designing TCP/IP?
(A) Marc Andreessen  (B) Ray Tomlinson  (C) Vint Cerf  (D) Tim Berners-Lee

✅ **Ans: (C) Vint Cerf** — With Bob Kahn

**4.** Where was the Mosaic web browser developed?
(A) CERN  (B) Microsoft  (C) Google  (D) NCSA

✅ **Ans: (D) NCSA** — Developed by Marc Andreessen's team at NCSA in 1993

**5.** URL stands for:
(A) Universal Resource Link  (B) Uniform Resource Locator  (C) Unique Record Locator  (D) Uniform Routing Link

✅ **Ans: (B) Uniform Resource Locator**

**6.** In `https://www.example.com/index.html`, what is `www.example.com`?
(A) the protocol  (B) the path  (C) the domain name  (D) the query string

✅ **Ans: (C) the domain name** — https = protocol, /index.html = path

**7.** Which top-level domain is used by educational institutions?
(A) .com  (B) .org  (C) .edu  (D) .net

✅ **Ans: (C) .edu**

**8.** An intranet is:
(A) a public network  (B) a private network inside an organisation that uses internet technologies  (C) a network of satellites  (D) a global WAN

✅ **Ans: (B) a private network inside an organisation that uses internet technologies**

**9.** An extranet is:
(A) an intranet that gives controlled access to outside partners  (B) the public internet  (C) a LAN only  (D) a satellite network

✅ **Ans: (A) an intranet that gives controlled access to outside partners**

**10.** Which of these is a search engine?
(A) Chrome  (B) Windows  (C) Gmail  (D) Google Search

✅ **Ans: (D) Google Search**

**11.** A web browser is:
(A) software used to view web pages  (B) a server  (C) a protocol  (D) a search engine

✅ **Ans: (A) software used to view web pages**

**12.** Where are cookies stored?
(A) on the web server  (B) on the client's browser/computer  (C) at the ISP  (D) on the DNS server

✅ **Ans: (B) on the client's browser/computer** — Small text files stored by the browser

**13.** Who sent the first e-mail over ARPANET?
(A) Ray Tomlinson  (B) Tim Berners-Lee  (C) Vint Cerf  (D) Steve Jobs

✅ **Ans: (A) Ray Tomlinson** — He introduced the @ sign

**14.** In an e-mail address, the "@" symbol separates:
(A) two domains  (B) the protocol and the host  (C) the user name and the domain name  (D) the server and the port

✅ **Ans: (C) the user name and the domain name**

**15.** HTML is used to:
(A) send e-mail  (B) create web pages  (C) route packets  (D) design databases

✅ **Ans: (B) create web pages**

**16.** Internet speed is measured in:
(A) bytes  (B) bits per second (bps)  (C) pixels  (D) hertz only

✅ **Ans: (B) bits per second (bps)**

**17.** Broadband means:
(A) high-speed, always-on internet access  (B) dial-up access  (C) satellite access only  (D) mobile access only

✅ **Ans: (A) high-speed, always-on internet access** — DSL, cable, fibre

**18.** Which organisation coordinates domain names and IP address allocation worldwide?
(A) W3C  (B) IEEE  (C) ICANN  (D) ISO

✅ **Ans: (C) ICANN** — IANA is part of ICANN

**19.** The W3C develops standards for:
(A) Ethernet  (B) mobile networks  (C) power supplies  (D) the web (HTML, CSS, XML)

✅ **Ans: (D) the web (HTML, CSS, XML)**

**20.** Dial-up internet uses:
(A) a telephone line and a modem  (B) optical fibre only  (C) satellite  (D) Wi-Fi

✅ **Ans: (A) a telephone line and a modem** — Max 56 kbps

---

## E. Network Devices

**1.** At which layer does a hub work?
(A) Physical  (B) Data Link  (C) Network  (D) Transport

✅ **Ans: (A) Physical**

**2.** A switch forwards frames using the:
(A) IP address  (B) MAC address  (C) port number  (D) domain name

✅ **Ans: (B) MAC address** — It learns MAC addresses into a MAC table

**3.** At which OSI layer does a router work?
(A) Layer 1  (B) Layer 2  (C) Layer 3  (D) Layer 4

✅ **Ans: (C) Layer 3**

**4.** A bridge:
(A) only amplifies signals  (B) connects two WANs at Layer 3  (C) converts between protocols  (D) connects two LAN segments at the Data Link Layer

✅ **Ans: (D) connects two LAN segments at the Data Link Layer**

**5.** A modem converts:
(A) digital signals to analog and back  (B) IP addresses to MAC addresses  (C) AC to DC  (D) text to voice

✅ **Ans: (A) digital signals to analog and back** — MOdulator–DEModulator

**6.** Which device sends incoming data out of all its ports?
(A) Switch  (B) Router  (C) Hub  (D) Bridge

✅ **Ans: (C) Hub**

**7.** A gateway:
(A) only amplifies signals  (B) connects networks that use different protocols  (C) works only at Layer 2  (D) is a type of cable

✅ **Ans: (B) connects networks that use different protocols** — Can work at all layers

**8.** A NIC has a:
(A) unique MAC address  (B) permanent IP address  (C) built-in DNS server  (D) fixed port number

✅ **Ans: (A) unique MAC address** — 48-bit MAC address burned in

**9.** At which layer does a repeater work?
(A) Data Link  (B) Network  (C) Physical  (D) Application

✅ **Ans: (C) Physical** — Regenerates the signal (PYQ 2025)

**10.** Which device separates collision domains but not broadcast domains?
(A) Hub  (B) Switch  (C) Router  (D) Repeater

✅ **Ans: (B) Switch**

**11.** Which device separates broadcast domains?
(A) Hub  (B) Repeater  (C) Switch  (D) Router

✅ **Ans: (D) Router**

**12.** A wireless access point is used to:
(A) connect wireless devices to a wired network  (B) encrypt hard disks  (C) convert analog signals  (D) route traffic between ISPs

✅ **Ans: (A) connect wireless devices to a wired network**

**13.** Which device sends a frame only to the port of the destination device?
(A) Repeater  (B) Switch  (C) Modem  (D) Hub

✅ **Ans: (B) Switch**

**14.** A brouter combines the functions of:
(A) a bridge and a repeater  (B) a hub and a switch  (C) a bridge and a router  (D) a modem and a router

✅ **Ans: (C) a bridge and a router**

**15.** Which device connects a home network to an ISP over a telephone line?
(A) DSL modem  (B) Hub  (C) Repeater  (D) Switch

✅ **Ans: (A) DSL modem**

**16.** A Layer-3 switch can also do:
(A) only signal repeating  (B) only amplification  (C) modulation  (D) routing (forwarding by IP address)

✅ **Ans: (D) routing (forwarding by IP address)**

**17.** How many collision domains does a 24-port switch create?
(A) 1  (B) 24  (C) 12  (D) 48

✅ **Ans: (B) 24** — One per port

**18.** How many broadcast domains does a 24-port switch have (no VLANs)?
(A) 1  (B) 24  (C) 2  (D) 12

✅ **Ans: (A) 1** — Only routers (or VLANs) split broadcast domains

**19.** A hub is also called a:
(A) multiport bridge  (B) router  (C) multiport repeater  (D) gateway

✅ **Ans: (C) multiport repeater**

**20.** Which device uses a routing table?
(A) Hub  (B) Repeater  (C) Router  (D) Modem

✅ **Ans: (C) Router**

---

## F. Transmission Modes & Media

**1.** A walkie-talkie works in which mode?
(A) Simplex  (B) Half duplex  (C) Full duplex  (D) None

✅ **Ans: (B) Half duplex** — Both directions, but one at a time

**2.** TV broadcasting is an example of:
(A) Simplex  (B) Half duplex  (C) Full duplex  (D) Multiplex

✅ **Ans: (A) Simplex** — One direction only. Keyboard → CPU is also simplex (PYQ 2019)

**3.** A telephone conversation is an example of:
(A) Simplex  (B) Half duplex  (C) Full duplex  (D) None

✅ **Ans: (C) Full duplex** — Mobile call = full duplex (PYQ 2025)

**4.** Optical fibre carries data as:
(A) electrical signals  (B) pulses of light  (C) radio waves  (D) sound waves

✅ **Ans: (B) pulses of light** — Fastest medium (PYQ 2019)

**5.** Optical fibre works on the principle of:
(A) total internal reflection  (B) refraction only  (C) diffraction  (D) interference

✅ **Ans: (A) total internal reflection**

**6.** The twisting in twisted-pair cable reduces:
(A) cost  (B) crosstalk and electromagnetic interference  (C) speed  (D) length

✅ **Ans: (B) crosstalk and electromagnetic interference** — Cat-5/5E/6 are twisted pair (PYQ 2025)

**7.** The RJ-45 connector is used with:
(A) coaxial cable  (B) optical fibre  (C) USB  (D) twisted-pair (Ethernet) cable

✅ **Ans: (D) twisted-pair (Ethernet) cable** — RJ-11 is for telephone lines

**8.** Coaxial cable is commonly used in:
(A) cable TV  (B) fibre-optic links  (C) Bluetooth  (D) infrared remotes

✅ **Ans: (A) cable TV**

**9.** Which of these is an unguided (wireless) medium?
(A) Twisted pair  (B) Coaxial cable  (C) Optical fibre  (D) Microwave

✅ **Ans: (D) Microwave** — Radio, microwave and infrared are unguided

**10.** Infrared communication requires:
(A) line of sight  (B) a cable  (C) a satellite  (D) a long range

✅ **Ans: (A) line of sight** — TV remote

**11.** Wi-Fi and Bluetooth use:
(A) infrared  (B) radio waves  (C) visible light  (D) sound

✅ **Ans: (B) radio waves** — 2.4/5 GHz

**12.** What is the unit of bit rate?
(A) baud  (B) Hz  (C) bps  (D) dB

✅ **Ans: (C) bps**

**13.** Baud rate measures:
(A) bits per second  (B) signal elements (symbols) per second  (C) bytes per minute  (D) errors per second

✅ **Ans: (B) signal elements (symbols) per second** — Bit rate = baud × bits per symbol

**14.** Serial transmission sends:
(A) one bit at a time over a single line  (B) many bits at once over many lines  (C) only whole bytes  (D) nothing

✅ **Ans: (A) one bit at a time over a single line** — Parallel = many bits at once (PYQ 2023)

**15.** In synchronous transmission, data is sent:
(A) one character at a time with start and stop bits  (B) as blocks, with sender and receiver sharing a clock  (C) only one character at a time  (D) without any timing

✅ **Ans: (B) as blocks, with sender and receiver sharing a clock**

**16.** Asynchronous transmission uses:
(A) only a clock signal  (B) large blocks  (C) no extra bits  (D) start and stop bits for each character

✅ **Ans: (D) start and stop bits for each character**

**17.** Which multiplexing method divides the bandwidth into separate frequency bands?
(A) TDM  (B) FDM  (C) WDM  (D) CDM

✅ **Ans: (B) FDM** — TDM = time slots

**18.** WDM (Wavelength Division Multiplexing) is used in:
(A) twisted pair  (B) coaxial cable  (C) optical fibre  (D) radio

✅ **Ans: (C) optical fibre** — It is FDM for light

**19.** What is the maximum length of a Cat-5/Cat-6 Ethernet segment?
(A) 100 m  (B) 500 m  (C) 1 km  (D) 10 m

✅ **Ans: (A) 100 m**

**20.** Satellite communication uses:
(A) microwaves  (B) infrared  (C) sound waves  (D) visible light

✅ **Ans: (A) microwaves**

---

## G. Data Link Layer

**1.** What is the data unit of the Data Link Layer?
(A) Bit  (B) Frame  (C) Packet  (D) Segment

✅ **Ans: (B) Frame** — Bit → Frame → Packet → Segment → Data

**2.** How long is a MAC address?
(A) 32 bits  (B) 64 bits  (C) 48 bits  (D) 128 bits

✅ **Ans: (C) 48 bits** — 12 hex digits (PYQ 2025)

**3.** MAC addresses are usually written in:
(A) decimal  (B) hexadecimal  (C) octal  (D) binary only

✅ **Ans: (B) hexadecimal** — e.g. 00:1A:2B:3C:4D:5E

**4.** What are the two sublayers of the Data Link Layer?
(A) LLC and MAC  (B) TCP and IP  (C) PHY and MAC  (D) LLC and IP

✅ **Ans: (A) LLC and MAC** — Logical Link Control + Media Access Control

**5.** Ethernet uses which access method?
(A) CSMA/CA  (B) Token passing  (C) Polling  (D) CSMA/CD

✅ **Ans: (D) CSMA/CD** — Contention-based (PYQ 2023, 2025)

**6.** Wi-Fi (IEEE 802.11) uses which access method?
(A) CSMA/CD  (B) CSMA/CA  (C) ALOHA only  (D) TDMA

✅ **Ans: (B) CSMA/CA** — Collision *avoidance*

**7.** Which IEEE standard is Token Ring?
(A) 802.3  (B) 802.11  (C) 802.5  (D) 802.15

✅ **Ans: (C) 802.5**

**8.** IEEE 802.3 is the standard for:
(A) Ethernet  (B) Wi-Fi  (C) Bluetooth  (D) Token Ring

✅ **Ans: (A) Ethernet** — 802.11 = Wi-Fi

**9.** CRC is used for:
(A) error detection  (B) encryption  (C) routing  (D) compression

✅ **Ans: (A) error detection** — Cyclic Redundancy Check

**10.** With even parity, what is the parity bit for the data 1011001?
(A) 1  (B) 0  (C) 2  (D) None

✅ **Ans: (B) 0** — It already has four 1s (even), so the parity bit is 0

**11.** Hamming code can:
(A) only detect errors  (B) detect and correct single-bit errors  (C) encrypt data  (D) compress data

✅ **Ans: (B) detect and correct single-bit errors**

**12.** To correct *d* errors, the minimum Hamming distance must be:
(A) d + 1  (B) 2d  (C) d  (D) 2d + 1

✅ **Ans: (D) 2d + 1** — To *detect* d errors you need d + 1

**13.** In Stop-and-Wait ARQ, the sender:
(A) sends one frame and waits for its acknowledgement  (B) sends many frames without waiting  (C) never waits for an ACK  (D) sends only NAKs

✅ **Ans: (A) sends one frame and waits for its acknowledgement**

**14.** In Go-Back-N ARQ, when a frame is lost, the sender retransmits:
(A) only the lost frame  (B) the lost frame and every frame after it  (C) nothing  (D) the whole file

✅ **Ans: (B) the lost frame and every frame after it**

**15.** Selective Repeat ARQ retransmits:
(A) all frames  (B) only the first frame  (C) only the lost or damaged frames  (D) nothing

✅ **Ans: (C) only the lost or damaged frames**

**16.** In HDLC bit stuffing, a 0 is inserted after:
(A) five consecutive 1s  (B) four consecutive 0s  (C) six consecutive 1s  (D) every byte

✅ **Ans: (A) five consecutive 1s**

**17.** What is the HDLC flag pattern?
(A) 11111111  (B) 01111110  (C) 10101010  (D) 00000000

✅ **Ans: (B) 01111110** — 0x7E

**18.** What is the maximum efficiency of pure ALOHA?
(A) 18.4%  (B) 36.8%  (C) 50%  (D) 100%

✅ **Ans: (A) 18.4%** — 1/(2e)

**19.** What is the maximum efficiency of slotted ALOHA?
(A) 18.4%  (B) 36.8%  (C) 25%  (D) 50%

✅ **Ans: (B) 36.8%** — 1/e

**20.** PPP (Point-to-Point Protocol) belongs to which layer?
(A) Network  (B) Transport  (C) Application  (D) Data Link

✅ **Ans: (D) Data Link**

---

## H. Transport Layer

**1.** What is the TCP data unit called?
(A) Frame  (B) Packet  (C) Segment  (D) Bit

✅ **Ans: (C) Segment** — Also called TPDU (PYQ 2025)

**2.** How does TCP set up a connection?
(A) 2-way handshake  (B) 3-way handshake  (C) 4-way handshake  (D) No handshake

✅ **Ans: (B) 3-way handshake**

**3.** What is the correct order of the TCP 3-way handshake?
(A) SYN → SYN-ACK → ACK  (B) ACK → SYN → FIN  (C) SYN → ACK → FIN  (D) FIN → ACK

✅ **Ans: (A) SYN → SYN-ACK → ACK**

**4.** Which TCP flag is used to close a connection?
(A) SYN  (B) FIN  (C) URG  (D) PSH

✅ **Ans: (B) FIN**

**5.** How big is the UDP header?
(A) 8 bytes  (B) 20 bytes  (C) 32 bytes  (D) 60 bytes

✅ **Ans: (A) 8 bytes**

**6.** What is the minimum size of a TCP header?
(A) 8 bytes  (B) 16 bytes  (C) 20 bytes  (D) 40 bytes

✅ **Ans: (C) 20 bytes** — Max 60 bytes

**7.** Which of these normally uses UDP?
(A) SMTP e-mail  (B) HTTP web pages  (C) DNS queries and live streaming  (D) FTP

✅ **Ans: (C) DNS queries and live streaming** — Speed matters more than reliability

**8.** Which protocol guarantees delivery and correct order?
(A) UDP  (B) IP  (C) ICMP  (D) TCP

✅ **Ans: (D) TCP**

**9.** Port numbers are:
(A) 8-bit  (B) 16-bit  (C) 32-bit  (D) 48-bit

✅ **Ans: (B) 16-bit** — 0–65535

**10.** What is the range of well-known ports?
(A) 0–1023  (B) 1024–49151  (C) 49152–65535  (D) 0–65535

✅ **Ans: (A) 0–1023** — 1024–49151 = registered ports, above that = dynamic

**11.** A socket is made up of:
(A) a MAC address + an IP address  (B) an IP address + a port number  (C) a port number only  (D) a domain name + an IP address

✅ **Ans: (B) an IP address + a port number** — (PYQ 2023, 2025)

**12.** Which mechanism is part of TCP congestion control?
(A) Slow start  (B) ALOHA  (C) CSMA  (D) Bit stuffing

✅ **Ans: (A) Slow start** — Plus congestion avoidance, fast retransmit

**13.** Flow control prevents:
(A) collisions  (B) routing loops  (C) a fast sender from overwhelming a slow receiver  (D) eavesdropping

✅ **Ans: (C) a fast sender from overwhelming a slow receiver** — TCP uses a sliding window (window advertisement, PYQ 2024)

**14.** The transport layer provides:
(A) node-to-node delivery  (B) process-to-process (end-to-end) delivery  (C) hop-to-hop delivery  (D) bit-level delivery

✅ **Ans: (B) process-to-process (end-to-end) delivery** — (PYQ 2024, 2025)

**15.** At the transport layer, different applications on one host are identified by:
(A) IP address  (B) MAC address  (C) port number  (D) TTL

✅ **Ans: (C) port number** — (PYQ 2020)

**16.** TCP is:
(A) connectionless  (B) a connection-oriented, reliable byte stream  (C) message-oriented and unreliable  (D) a Layer-2 protocol

✅ **Ans: (B) a connection-oriented, reliable byte stream**

**17.** Which TCP header field lets the receiver put data back in order?
(A) Sequence number  (B) TTL  (C) Checksum only  (D) Window size

✅ **Ans: (A) Sequence number** — ACK number confirms receipt

**18.** In UDP over IPv4, the checksum is:
(A) not present  (B) used for encryption  (C) always zero  (D) optional

✅ **Ans: (D) optional** — Mandatory in IPv6

**19.** Which application suits UDP best?
(A) Online video calling  (B) File download  (C) E-mail  (D) Online banking website

✅ **Ans: (A) Online video calling**

**20.** SCTP stands for:
(A) Simple Control Transfer Protocol  (B) Secure Channel Transport Protocol  (C) Stream Control Transmission Protocol  (D) Session Control Transport Protocol

✅ **Ans: (C) Stream Control Transmission Protocol**

---

## I. Network Layer & Routing

**1.** What is the data unit of the Network Layer?
(A) Frame  (B) Packet (datagram)  (C) Segment  (D) Bit

✅ **Ans: (B) Packet (datagram)**

**2.** The Network Layer is responsible for:
(A) host-to-host delivery and routing  (B) process-to-process delivery  (C) framing  (D) sending raw bits

✅ **Ans: (A) host-to-host delivery and routing** — Routing = finding the best path (PYQ 2023)

**3.** Static routing means routes are:
(A) learned automatically  (B) learned through RIP  (C) entered manually by the administrator  (D) learned through BGP

✅ **Ans: (C) entered manually by the administrator**

**4.** What metric does RIP use?
(A) Hop count  (B) Bandwidth  (C) Delay  (D) Cost

✅ **Ans: (A) Hop count**

**5.** What is the maximum hop count allowed in RIP?
(A) 16  (B) 255  (C) 15  (D) 10

✅ **Ans: (C) 15** — 16 = unreachable

**6.** OSPF is a:
(A) distance-vector protocol  (B) link-state protocol  (C) path-vector protocol  (D) static protocol

✅ **Ans: (B) link-state protocol**

**7.** BGP is used:
(A) inside a single LAN  (B) as a link-state protocol  (C) at the Data Link Layer  (D) between autonomous systems (exterior gateway protocol)

✅ **Ans: (D) between autonomous systems (exterior gateway protocol)**

**8.** Dijkstra's shortest-path algorithm is used in:
(A) OSPF  (B) RIP  (C) BGP  (D) ARP

✅ **Ans: (A) OSPF**

**9.** The Bellman–Ford algorithm is the basis of:
(A) OSPF  (B) distance-vector routing (RIP)  (C) SSL  (D) DNS

✅ **Ans: (B) distance-vector routing (RIP)**

**10.** The count-to-infinity problem occurs in:
(A) link-state routing  (B) distance-vector routing  (C) static routing  (D) flooding

✅ **Ans: (B) distance-vector routing**

**11.** ICMP is used for:
(A) error reporting and diagnostics  (B) file transfer  (C) e-mail  (D) encryption

✅ **Ans: (A) error reporting and diagnostics** — Used by ping

**12.** `traceroute`/`tracert` works using:
(A) ARP  (B) DHCP  (C) TTL values and ICMP messages  (D) SMTP

✅ **Ans: (C) TTL values and ICMP messages**

**13.** Fragmentation happens when:
(A) a packet is larger than the MTU of the next link  (B) a packet is too small  (C) an error is detected  (D) a packet is encrypted

✅ **Ans: (A) a packet is larger than the MTU of the next link** — Ethernet MTU = 1500 bytes

**14.** The default gateway is:
(A) the DNS server  (B) a switch  (C) the modem only  (D) the router that forwards packets to other networks

✅ **Ans: (D) the router that forwards packets to other networks**

**15.** An autonomous system (AS) is:
(A) a group of networks under one administrative control  (B) a single PC  (C) one router  (D) a protocol

✅ **Ans: (A) a group of networks under one administrative control**

**16.** In flooding, a router sends each incoming packet:
(A) along a single path  (B) out of every outgoing line except the one it arrived on  (C) nowhere  (D) only at Layer 2

✅ **Ans: (B) out of every outgoing line except the one it arrived on**

**17.** Which of these is a *routed* protocol rather than a *routing* protocol?
(A) IP  (B) RIP  (C) OSPF  (D) BGP

✅ **Ans: (A) IP** — IP is carried. RIP, OSPF and BGP build routing tables.

**18.** IGMP manages:
(A) unicast routing  (B) ARP tables  (C) multicast group membership  (D) DNS records

✅ **Ans: (C) multicast group membership**

**19.** Traditional telephone networks use:
(A) packet switching  (B) circuit switching  (C) message switching  (D) none of these

✅ **Ans: (B) circuit switching** — The Internet uses packet switching (PYQ 2019)

**20.** Message switching is also known as:
(A) store-and-forward switching  (B) cut-through switching  (C) circuit switching  (D) virtual-circuit switching

✅ **Ans: (A) store-and-forward switching**

---

## J. Network Types & Topology

**1.** In which topology is every device connected to a central hub or switch?
(A) Bus  (B) Star  (C) Ring  (D) Mesh

✅ **Ans: (B) Star**

**2.** How many links does a full mesh of *n* nodes need?
(A) n  (B) n − 1  (C) n(n − 1)/2  (D) n²

✅ **Ans: (C) n(n − 1)/2**

**3.** Which topology uses a single backbone cable?
(A) Star  (B) Ring  (C) Bus  (D) Tree

✅ **Ans: (C) Bus**

**4.** In which topology does the whole network fail if the central device fails?
(A) Mesh  (B) Ring  (C) Bus  (D) Star

✅ **Ans: (D) Star** — Single point of failure

**5.** In a ring topology, data travels:
(A) in one direction, passing through each node  (B) randomly  (C) only through a central node  (D) to all nodes at once

✅ **Ans: (A) in one direction, passing through each node** — A dual ring can use both directions

**6.** Which topology is the most fault-tolerant?
(A) Mesh  (B) Bus  (C) Star  (D) Ring

✅ **Ans: (A) Mesh**

**7.** A tree topology combines:
(A) ring and mesh  (B) bus and ring  (C) star and bus  (D) none of these

✅ **Ans: (C) star and bus**

**8.** A LAN typically covers:
(A) a building or campus  (B) a city  (C) a country  (D) the whole world

✅ **Ans: (A) a building or campus**

**9.** Which is an example of a MAN?
(A) a home network  (B) a cable-TV network across a city  (C) the Internet  (D) a Bluetooth link

✅ **Ans: (B) a cable-TV network across a city**

**10.** What is the largest WAN?
(A) The Internet  (B) An intranet  (C) A LAN  (D) A PAN

✅ **Ans: (A) The Internet**

**11.** Which is an example of a PAN?
(A) a city network  (B) the Internet  (C) a campus network  (D) a phone connected to Bluetooth earphones

✅ **Ans: (D) a phone connected to Bluetooth earphones** — Range of about 10 m

**12.** In a peer-to-peer network:
(A) each computer can act as both client and server  (B) there is a dedicated server  (C) nothing can be shared  (D) there is only one client

✅ **Ans: (A) each computer can act as both client and server**

**13.** How many cables does a full mesh of 5 nodes need?
(A) 5  (B) 10  (C) 20  (D) 25

✅ **Ans: (B) 10** — 5 × 4 / 2 = 10

**14.** How many cables does a star network of *n* nodes need (one central switch)?
(A) n  (B) n − 1  (C) n(n − 1)/2  (D) 1

✅ **Ans: (A) n**

**15.** Unicast communication is:
(A) one-to-all  (B) one-to-group  (C) one-to-one  (D) none of these

✅ **Ans: (C) one-to-one** — Broadcast = one-to-all (PYQ 2019)

**16.** Multicast communication is:
(A) one-to-one  (B) one-to-group  (C) one-to-all  (D) none of these

✅ **Ans: (B) one-to-group**

**17.** A logical topology describes:
(A) how data flows through the network  (B) the physical cable layout  (C) the power supply  (D) none of these

✅ **Ans: (A) how data flows through the network**

**18.** Which topology needs terminators at both ends of the cable?
(A) Star  (B) Bus  (C) Mesh  (D) Ring

✅ **Ans: (B) Bus**

**19.** A hybrid topology is:
(A) star only  (B) bus only  (C) wireless only  (D) a combination of two or more topologies

✅ **Ans: (D) a combination of two or more topologies**

**20.** SAN stands for:
(A) System Access Network  (B) Storage Area Network  (C) Server Allocation Network  (D) Secure Area Network

✅ **Ans: (B) Storage Area Network**

---

## K. Multimedia Networking

**1.** Jitter is:
(A) variation in packet delay  (B) packet loss  (C) bandwidth  (D) compression

✅ **Ans: (A) variation in packet delay** — Caused by delay between packets (PYQ 2023)

**2.** Jitter is reduced by using a:
(A) faster CPU  (B) firewall  (C) playout (jitter) buffer  (D) DNS server

✅ **Ans: (C) playout (jitter) buffer**

**3.** RTP stands for:
(A) Remote Transfer Protocol  (B) Real-time Transport Protocol  (C) Real-Time Packet  (D) Routing Transport Protocol

✅ **Ans: (B) Real-time Transport Protocol**

**4.** RTP usually runs over:
(A) TCP  (B) UDP  (C) ICMP  (D) ARP

✅ **Ans: (B) UDP**

**5.** RTCP is used for:
(A) monitoring quality and sending feedback for RTP sessions  (B) e-mail  (C) file transfer  (D) routing

✅ **Ans: (A) monitoring quality and sending feedback for RTP sessions** — Real-time Transport Control Protocol

**6.** RTSP is used to:
(A) send mail  (B) resolve domain names  (C) assign IP addresses  (D) control a streaming server (play, pause, teardown)

✅ **Ans: (D) control a streaming server (play, pause, teardown)** — Teardown = the server ends the session (PYQ 2023)

**7.** Which of these is a lossy compression format?
(A) ZIP  (B) PNG  (C) JPEG / MP3  (D) TXT

✅ **Ans: (C) JPEG / MP3**

**8.** Which of these is a lossless compression format?
(A) ZIP  (B) JPEG  (C) MP3  (D) MPEG-4

✅ **Ans: (A) ZIP** — PNG and GIF are lossless too

**9.** MPEG is used mainly to compress:
(A) video  (B) text  (C) e-mail  (D) routing tables

✅ **Ans: (A) video**

**10.** What is the correct order of steps in PCM?
(A) Encoding → Sampling → Quantization  (B) Sampling → Quantization → Encoding  (C) Quantization → Encoding → Sampling  (D) Encryption → Encoding

✅ **Ans: (B) Sampling → Quantization → Encoding** — Converts analog to digital (PYQ 2020)

**11.** By the Nyquist theorem, the sampling rate must be at least:
(A) twice the highest frequency  (B) equal to the highest frequency  (C) half the highest frequency  (D) four times the highest frequency

✅ **Ans: (A) twice the highest frequency**

**12.** Voice with a 4 kHz bandwidth must be sampled at:
(A) 4,000 samples/s  (B) 8,000 samples/s  (C) 16,000 samples/s  (D) 2,000 samples/s

✅ **Ans: (B) 8,000 samples/s** — 2 × 4 kHz (PYQ 2023: 8,000 samples/s)

**13.** What is the bit rate of standard telephone PCM (8,000 samples/s × 8 bits)?
(A) 32 kbps  (B) 56 kbps  (C) 64 kbps  (D) 128 kbps

✅ **Ans: (C) 64 kbps**

**14.** When streaming stored audio or video, playback begins:
(A) only after the full file has downloaded  (B) while the file is still downloading  (C) never  (D) only offline

✅ **Ans: (B) while the file is still downloading**

**15.** A VoIP call is an example of:
(A) real-time interactive audio  (B) streaming stored audio  (C) e-mail  (D) file transfer

✅ **Ans: (A) real-time interactive audio**

**16.** Which of these are QoS parameters?
(A) Font  (B) Colour  (C) CPU speed  (D) Delay, jitter, bandwidth and packet loss

✅ **Ans: (D) Delay, jitter, bandwidth and packet loss**

**17.** MP3 is:
(A) an audio compression format  (B) a video format  (C) an image format  (D) a network protocol

✅ **Ans: (A) an audio compression format**

**18.** Codec stands for:
(A) code checker  (B) coder–decoder  (C) computer decoder  (D) content collector

✅ **Ans: (B) coder–decoder** — Also read as compressor–decompressor

**19.** Which transport protocol suits live streaming better?
(A) UDP  (B) TCP only  (C) SMTP  (D) FTP

✅ **Ans: (A) UDP** — A late packet is useless anyway

**20.** Buffering in video streaming mainly handles:
(A) screen size  (B) codec licences  (C) variation in network delay (jitter)  (D) DNS lookups

✅ **Ans: (C) variation in network delay (jitter)**

---

## L. Wireless & IoT Networking

**1.** Wi-Fi is defined by which IEEE standard?
(A) 802.3  (B) 802.11  (C) 802.15.1  (D) 802.5

✅ **Ans: (B) 802.11**

**2.** Bluetooth is defined by which IEEE standard?
(A) 802.11  (B) 802.3  (C) 802.15.1  (D) 802.16

✅ **Ans: (C) 802.15.1**

**3.** ZigBee is based on:
(A) IEEE 802.15.4  (B) IEEE 802.11  (C) IEEE 802.3  (D) IEEE 802.16

✅ **Ans: (A) IEEE 802.15.4** — ZigBee is a task group under IEEE 802.15 (PYQ 2025)

**4.** WiMAX is defined by which IEEE standard?
(A) 802.11  (B) 802.15  (C) 802.3  (D) 802.16

✅ **Ans: (D) 802.16**

**5.** A small Bluetooth network of up to 8 active devices is called a:
(A) Piconet  (B) Scatternet  (C) WLAN  (D) MANET

✅ **Ans: (A) Piconet** — 1 master + 7 active slaves

**6.** Two or more connected piconets form a:
(A) Piconet  (B) Scatternet  (C) Mesh  (D) Star

✅ **Ans: (B) Scatternet**

**7.** Bluetooth operates in which band?
(A) 2.4 GHz ISM  (B) 5.8 GHz only  (C) 900 MHz  (D) 60 GHz

✅ **Ans: (A) 2.4 GHz ISM**

**8.** Which ZigBee device starts and manages the network?
(A) Coordinator  (B) Router  (C) End device  (D) Gateway

✅ **Ans: (A) Coordinator** — The ZigBee router relays data between devices (PYQ 2025)

**9.** Which lightweight publish–subscribe protocol is popular in IoT?
(A) FTP  (B) SMTP  (C) MQTT  (D) Telnet

✅ **Ans: (C) MQTT** — Message Queuing Telemetry Transport (PYQ 2025)

**10.** CoAP is designed for:
(A) constrained (low-power) IoT devices  (B) e-mail  (C) file sharing  (D) video streaming

✅ **Ans: (A) constrained (low-power) IoT devices** — Constrained Application Protocol

**11.** RFID stands for:
(A) Radio Field Identification  (B) Remote Frequency Identification  (C) Radio Fast Identification  (D) Radio Frequency Identification

✅ **Ans: (D) Radio Frequency Identification**

**12.** What is the typical range of NFC?
(A) about 4 cm  (B) 100 m  (C) 1 km  (D) 10 m

✅ **Ans: (A) about 4 cm**

**13.** LoRaWAN is best suited for:
(A) long-range, low-power communication  (B) short-range, high-speed links  (C) wired networks  (D) satellite TV

✅ **Ans: (A) long-range, low-power communication**

**14.** An SSID is:
(A) a MAC address  (B) the name of a Wi-Fi network  (C) an IP address  (D) a password

✅ **Ans: (B) the name of a Wi-Fi network** — Service Set Identifier

**15.** Which of these is the most secure Wi-Fi security protocol?
(A) WEP  (B) WPA  (C) WPA3  (D) Open (no security)

✅ **Ans: (C) WPA3** — WEP is the weakest

**16.** Which technology is the standard for 4G?
(A) LTE  (B) GSM  (C) GPRS  (D) AMPS

✅ **Ans: (A) LTE** — Long Term Evolution. "G" = Generation (PYQ 2020, 2025)

**17.** 1G mobile networks provided:
(A) analog voice  (B) digital voice and SMS  (C) mobile broadband  (D) IoT connectivity

✅ **Ans: (A) analog voice** — 2G = digital voice + SMS

**18.** GSM stands for:
(A) General System for Mobile  (B) Global Signal Mode  (C) Global System for Mobile Communications  (D) Global Satellite Mobile

✅ **Ans: (C) Global System for Mobile Communications**

**19.** MANET stands for:
(A) Mobile Ad hoc Network  (B) Metropolitan Area Network  (C) Managed Network  (D) Multiple Access Network

✅ **Ans: (A) Mobile Ad hoc Network**

**20.** A Wi-Fi hotspot is:
(A) a virus  (B) a type of cable  (C) a routing protocol  (D) a place or device that offers wireless internet access

✅ **Ans: (D) a place or device that offers wireless internet access**

---

### Score tracker

| Topic | Attempt 1 | Attempt 2 |
|---|---|---|
| A. Protocols | /20 | /20 |
| B. Security | /20 | /20 |
| C. IP addressing | /20 | /20 |
| D. Internet basics | /20 | /20 |
| E. Devices | /20 | /20 |
| F. Transmission & media | /20 | /20 |
| G. Data Link Layer | /20 | /20 |
| H. Transport layer | /20 | /20 |
| I. Network layer & routing | /20 | /20 |
| J. Types & topology | /20 | /20 |
| K. Multimedia | /20 | /20 |
| L. Wireless & IoT | /20 | /20 |
| **Total** | **/240** | **/240** |
