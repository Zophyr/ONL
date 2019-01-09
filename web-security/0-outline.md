Part 1. Explanation of Terms, 30 points 
NOTE: Give the definitions or explanations of the following terms, 5points for each. 
(1) Data Integrity 
Assures that information and programs are changed only in a specified and authorized 
manner. 
In information security, integrity means that data cannot be modified undetectably. 
Integrity is violated when a message is actively modified in transit.Information security 
systems typically provide message integrity in additionto data confidentiality 
(2) Information Security Audit 
An information security audit is an audit on the level of information securityin an 
organization 
(3) PKI 
PKI provides well-conceived infrastructures to deliver security services inan efficient and 
unified style. PKI is a long-term solution that can be used toprovide a large spectrum of 
security protection. 
(4) X.509 
In cryptography, X.509 is an ITU-T standard for a public key infrastructure (PKI) for single sign-on (SSO, 单点登录 ) and Privilege Management Infrastructure (PMI, 特权管理基础架 构). 
The ITU-T recommendation X.509 defines a directory service thatmaintains a database of information about users for the provision ofauthentication services ⋯ (5) Denial-of-Service Attack 
DoS (Denial of Service) is an attempt by attackers to make a computerresource unavailable to 
its intended users. 
(6) SOA(Service-Oriented Architecture) 
SOA is a flexible set of design principles used during the phases of systems development and 
integration in computing. A system based on a SOA will package functionality as a suite of 
interoperable services that can be used within multiple, separate systems from several 
business domains. 
(7) Access Control 
Access control is a system that enables an authority tocontrol access to areas and resources in a given physical facility or computer ‐based information system. An access control system, 
within the field of physical security, isgenerally seen as the second layer in the security of a 
physical structure. 
(Access control refers to exerting control over who can interact with a resource. Often but 
not always, this involves an authority, who does the controlling. The resource can be a given 
building, group of buildings, or computer-based information system. But it can also refer to a 
restroom stall where access is controlled by using a coin to open the door) 
(8) Salted Value 
In cryptography, a salt consists of random bits, creating one of the inputs to a one-way 
function. The other input is usually a password or passphrase. The output of the one-way 
function can be stored (alongside the salt) rather than the password, and still be used for 
authenticating users. The one-way function typically uses a cryptographic hash function. A 
salt can also be combined with a password by a key derivation function such as PBKDF2 to 
generate a key for use with a cipher or other cryptographic algorithm. The benefit provided 
by using a salted password is making a lookup table assisted dictionary attack against the 
stored values impractical, provided the salt is large enough. That is, an attacker would not be 
able to create a precomputed lookup table (i.e. a rainbow table) of hashed values (password 

- salt), because it would require a large computation for each salt. 
  (9) SOAP 
  SOAP is a protocol specification for exchanging structured information in the implementation 
  of Web Services in computer networks. It relies on Extensible Markup Language (XML) for its 
  message format, and usually relies on other Application Layer protocols, most notably 
  Hypertext Transfer Protocol (HTTP) and Simple Mail Transfer Protocol (SMTP), for message 
  negotiation and transmission 
  (10)Confidentiality 
  Confidentiality is the term used to prevent the disclosure of information to unauthorized 
  individuals or systems. Confidentiality is necessary (but not sufficient) for maintaining the 
  privacy of the people whose personal information a system holds. 
  (11)Authentication 
  In computing, e-Business and information security is necessary to ensure that the data, 
  transactions, communications or documents (electronic or physical) are genuine. It is also 
  important for authenticity to validate that both parties involved are who they claim they are. 
  (12)Kerberos 
  Kerberos is an authentication service developed at MIT which allows a distributed system to 
  be able to authenticate requests for service generated from workstations. 
  Kerberos (ITU-T) is a computer network authentication protocol which works on the basis of “ tickets” to allow nodes communicating over a non-secure network to prove their identity to 
  one another in a secure manner. 
  (13)SSL/TLS 
  SSL are cryptographic protocols that provide communication security over the Internet. TLS 
  and its predecessor, SSL encrypt the segments of network connections above the Transport 
  Layer, using asymmetric cryptography for key exchange, symmetric encryption for privacy, 
  and message authentication codes for message integrity. 
  (14)Man-in-the-Middle Attack 
  Man-in-the-Middle Attack is a form of active eavesdropping in which the attacker 
  makesindependent connections with the victims and relays messages between them, making 
  them believe that they are talking directly to each other over a private connection, when in 
  fact the entire conversation is controlled by the attacker. 
  (15)System Vulnerability A vulnerability is a flaw or weakness in a system ’s design, implementation, or operation and management that could be exploited to violate the system ’s security policy (which allows an attacker to reduce a system's information assurance). Vulnerability is the intersection of 
  three elements: a system susceptibility or flaw, attacker access to the flaw, and attacker 
  capability to exploit the flaw. 
  (16)Non-Repudiation 
  Non-repudiation refers to a state of affairs where the author of a statement will not be able 
  to successfully challenge the authorship of the statement or validity of an associated contract. 
  The term is often seen in a legal setting wherein the authenticity of a signature is being 
  challenged. In such an instance, the authenticity is being "repudiated". 
  (17)Bastion Host 
  A bastion host is a computers on a network, specifically designed and configured to withstand attacks. It’ s identified by the firewall admin as a critical strong point in the network ’ s security. The firewalls (application ‐level or circuit ‐level gateways) and routers 
  can be considered bastion hosts. Other types of bastion hosts include web, mail, DNS, and 
  FTP servers. 
  (18)CSRF 
  Cross-Site Request Forgery (CSRF) is an attack that forces an end user to execute unwanted 
  actions on a web application in which they're currently authenticated. CSRF attacks 
  specifically target state-changing requests, not theft of data, since the attacker has no way to 
  see the response to the forged request. With a little help of social engineering (such as 
  sending a link via email or chat), an attacker may trick the users of a web application into 
  executing actions of the attacker's choosing. If the victim is a normal user, a successful CSRF 
  attack can force the user to perform state changing requests like transferring funds, changing 
  their email address, and so forth. If the victim is an administrative account, CSRF can 
  compromise the entire web application. 
  Part 2. Brief Questions, 40 points 
  NOTE: Answer the following HOW TO questions in brief, 8 points foreach. 
  (1) Asymmetric Cryptographic Method. 非对称加密算法需要两个密钥： 公开密钥 (public‐key) 和私有密钥 (private‐key)。公开 密钥与私有密钥一一配对，如果用一个公开密钥对数据进行加密，则只有用其对应的私 有密钥才能实施解密；如果用一个私有密钥对数据进行加密，那么也只有用其对应的公 开密钥才能解密。加密和解密使用的是两个不同的密钥，所以这种算法被称为非对称加 密算法。 具体在 2.3.1 
  (2) Security in Cloud Computing: How to discern the Security in CloudComputing in your point 
  of view. 
  The responsibility goes both ways, however: the provider must ensure that their infrastructure is secure and that their clients ’ data and applications are protected while 
  the user must take measures to fortify their application and use strong passwords and 
  authentication measures. 
  (3) MD5: How to be used for password protection. 平时作业中布置了
  (4) ARP Poisoning: How to carry out an ARP Cache Poisoning Attack. 
  (5) Vulnerabilities of Firewall: How to penetrate a firewall, illustrated with atleast 3 examples. 
  (6) Kerberos: How Kerberos works 
  (7) Packet Filtering Firewall: How to penetrate a packet filtering firewall. 
  (8) SQL Injection: How to carry out a SQL Injection. 
  (9) RSA: How to be used for Digital Signatures. 
  (10)Salted Value: How to be used to enhance Hash security. 
  (11)Stateful Inspection Firewall: How to penetrate a stateful firewall. 
  (12)XSS: How to carry out an XSS Attack. 
  (13)PDCA Cycle or Deming Ring method: How to be used in Implementation of ISM. 
  (14)DES: How to release/manage the private key of DES. 
  The key-schedule of DES 
  Figureillustratesthe key schedule for encryption —the algorithm which generates the 
  subkeys. Initially, 56 bits of the key are selected 
  from the initial 64 by Permuted Choice 1 (PC-1)—the remaining eight bits are either 
  discarded or used as parity check bits. The 56 bits 
  are then divided into two 28-bit halves; each half is 
  thereafter treated separately. In successive rounds, 
  both halves are rotated left by one or two bits 
  (specified for each round), and then 48 subkey bits are selected by Permuted Choice 2 (PC-2) —24 bits 
  from the left half, and 24 from the right. The 
  rotations (denoted by "<<<" in the diagram) mean 
  that a different set of bits is used in each subkey; 
  each bit is used in approximately 14 out of the 16 
  subkeys. The key schedule for decryption is similar—the subkeys are in reverse order compared to 
  encryption. Apart from that change, the process is 
  the same as for encryption. The same 28 bits are 
  passed to all rotation boxes. 
  (15)IP Spoofing: How to carry out an IP Spoofing attack. 
  What Is a Spoofing Attack? 
  A spoofing attack is when a malicious party impersonates another device or user on a 
  network in order to launch attacks against network hosts, steal data, spread malware or 
  bypass access controls. There are several different types of spoofing attacks that malicious 
  parties can use to accomplish this. Some of the most common methods include IP address 
  spoofing attacks, ARP spoofing attacks and DNS server spoofing attacks. 
  IP Address Spoofing Attacks 
  IP address spoofing is one of the most frequently used spoofing attack methods. In an IP address spoofing attack, an attacker sends IP packets from a false (or “spoofed ”) source address in order to disguise itself. Denial-of-service attacks often use IP spoofing to overload 
  networks and devices with packets that appear to be from legitimate source IP addresses. 
  There are two ways that IP spoofing attacks can be used to overload targets with traffic. 
  One method is to simply flood a selected target with packets from multiple spoofed 
  addresses. This method works by directly sending a victim more data than it can handle. The other method is to spoof the target ’s IP address and send packets from that address to many 
  different recipients on the network. When another machine receives a packet, it will 
  automatically transmit a packet to the sender in response. Since the spoofed packets appear to be sent from the target ’s IP address, all responses to the spoofed packets will be sent to 
  (and flood) the target ’s IP address. IP spoofing attacks can also be used to bypass IP address-based authentication. This 
  process can be very difficult and is primarily used when trust relationships are in place 
  between machines on a network and internal systems. Trust relationships use IP addresses (rather than user log ins) to verify machines ’ identities when attempting to access systems. 
  This enables malicious parties to use spoofing attacks to impersonate machines with access 
  permissions and bypass trust-based network security measures. 
  ARP Spoofing Attacks 
  ARP is short for Address Resolution Protocol, a protocol that is used to resolve IP 
  addresses to MAC (Media Access Control) addresses for transmitting data. In an ARP spoofing 
  attack, a malicious party sends spoofed ARP messages across a local area network in order to link the attacker ’s MAC address with the IP address of a legitimate member of the network. This type of spoofing attack results in data that is intended for the host ’s IP address getting 
  sent to the attacker instead. Malicious parties commonly use ARP spoofing to steal 
  information, modify data in-transit or stop traffic on a LAN. ARP spoofing attacks can also be 
  used to facilitate other types of attacks, including denial-of-service, session hijacking and 
  man-in-the-middle attacks. ARP spoofing only works on local area networks that use the 
  Address Resolution Protocol. 
  DNS Server Spoofing Attacks 
  The Domain Name System (DNS) is a system that associates domain names with IP 
  addresses. Devices that connect to the internet or other private networks rely on the DNS for 
  resolving URLs, email addresses and other human-readable domain names into their 
  corresponding IP addresses. In a DNS server spoofing attack, a malicious party modifies the 
  DNS server in order to reroute a specific domain name to a different IP address. In many 
  cases, the new IP address will be for a server that is actually controlled by the attacker and 
  contains files infected with malware. DNS server spoofing attacks are often used to spread 
  computer worms and viruses. 
  Spoofing Attack Prevention and Mitigation 
  There are many tools and practices that organizations can employ to reduce the threat 
  of spoofing attacks. Common measures that organizations can take for spoofing attack 
  prevention include: 
  Packet filtering: Packet filters inspect packets as they are transmitted across a network. 
  Packet filters are useful in IP address spoofing attack prevention because they are capable of 
  filtering out and blocking packets with conflicting source address information (packets from 
  outside the network that show source addresses from inside the network and vice-versa). 
  Avoid trust relationships: Organizations should develop protocols that rely on trust 
  relationships as little as possible. It is significantly easier for attackers to run spoofing attacks 
  when trust relationships are in place because trust relationships only use IP addresses for 
  authentication. 
  Use spoofing detection software: There are many programs available that help 
  organizations detect spoofing attacks, particularly ARP spoofing. These programs work by 
  inspecting and certifying data before it is transmitted and blocking data that appears to be 
  spoofed. 
  Use cryptographic network protocols: Transport Layer Security (TLS), Secure Shell (SSH), HTTP 
  Secure (HTTPS) and other secure communications protocols bolster spoofing attack 
  prevention efforts by encrypting data before it is sent and authenticating data as it is 
  received. 
  (16)HIDS: How to carry out Intrusion Detection by making use of HIDS. 
  Part 3. Essay Questions, 30 points 
  NOTE: Discuss the following questions in detail, 10 points for each. 
  (1) Discuss some PORT SCAN Software you ever used, including the usageand the running result 
  analysis. 
  (2) Discuss the mechanisms of Buffer Overflow in illustration of some realexample. 
  (3) Select one from the OWASP ’s Top Ten Threatens of Web Applications2013 and discuss the mechanisms, citing in illustration. 
  (4) Discuss the mechanisms of IPSec in Transport Mode . 
  (5) Discuss the mechanisms of IPSec in Tunnel Mode . 
  (6) The web server vulnerabilities may cause some kinds of attacks. Try to find them and discuss 
  the consequences in brief. 
  (7) Discuss the mechanisms of SSL and show me how it works with HTTP .
  mechanisms of SSL 
  SSL uses a combination of public key and symmetric key encryption to secure a connection between two machines, typically a web or mail server and a client system, communicating over the internet or another TCP/IP network. SSL provides a mechanism for encrypting and authenticating data sent between processes running on a client and server. 
  SSL runs above the transport layer and the network layer, which are responsible for the transport of data between processes and the routing of network traffic over a network between client and server, respectively, and below application layer protocols such as HTTP and the Simple Mail Transport Protocol. The "sockets" part of the term refers to the sockets method of passing data between a client and a server program in a network or between processes in the same computer. 
  How Does HTTPS Work? 
  HTTPS pages typically use one of two secure protocols to encrypt communications - SSL (Secure Sockets Layer) or TLS (Transport Layer Security). Both the TLS and SSL protocols use what is known as an 'asymmetric' Public Key Infrastructure (PKI) system. An asymmetric system uses two 'keys' to encrypt communications, a 'public' key and a 'private' key. Anything encrypted with the public key can only be decrypted by the private key and vice-versa. 
  As the names suggest, the 'private' key should be kept strictly protected and should only be accessible the owner of the private key. In the case of a website, the private key remains securely ensconced on the web server. Conversely, the public key is intended to be distributed to anybody and everybody that needs to be able to decrypt information that was encrypted with the private key. 
  What is a HTTPS certificate? 
  When you request a HTTPS connection to a webpage, the website will initially send its SSL certificate to your browser. This certificate contains the public key needed to begin the secure session. Based on this initial exchange, your browser and the website then initiate the 'SSL handshake'. The SSL handshake involves the generation of shared secrets to establish a uniquely secure connection between yourself and the website. 
  When a trusted SSL Digital Certificate is used during a HTTPS connection, users will see a padlock icon in the browser address bar. When an Extended Validation Certificate is installed on a web site, the address bar will turn green. 
  How does HTTPS actually work?
  27 Mar 2014 

1. What is HTTPS and what does it do? 
   HTTPS takes the well-known and understood HTTP protocol, and simply layers a SSL/TLS (hereafter referred to simply as “SSL”) encryption layer on top of it. Servers and clients still speak exactly the same HTTP to each other, but over a secure SSL connection that encrypts and decrypts their requests and responses. The SSL layer has 2 main purposes: 
   Verifying that you are talking directly to the server that you think you are talking to 
   Ensuring that only the server can read what you send it and only you can read what it sends back 
   The really, really clever part is that anyone can intercept every single one of the messages you exchange with a server, including the ones where you are agreeing on the key and encryption strategy to use, and still not be able to read any of the actual data you send. 
2. How an SSL connection is established 
   An SSL connection between a client and server is set up by a handshake, the goals of which are: 
   To satisfy the client that it is talking to the right server (and optionally visa versa) 
   For the parties to have agreed on a “cipher suite ”, which includes which encryption algorithm they will use to exchange data 
   For the parties to have agreed on any necessary keys for this algorithm 
   Once the connection is established, both parties can use the agreed algorithm and keys to securely send messages to each other. We will break the handshake up into 3 main phases - Hello, Certificate Exchange and Key Exchange. 
3. Hello - The handshake begins with the client sending a ClientHello message. This contains all 
   the information the server needs in order to connect to the client via SSL, including the various cipher suites and maximum SSL version that it supports. The server responds with a ServerHello, which contains similar information required by the client, including a decision based on the client ’s preferences about which cipher suite and version of SSL will be used.
4. Certificate Exchange - Now that contact has been established, the server has to prove its identity to the client. This is achieved using its SSL certificate, which is a very tiny bit like its passport. An SSL certificate contains various pieces of data, including the name of the owner, the property (eg. domain) it is attached to, the certificate ’s public key, the digital signature and information about the certificate ’s validity dates. The client checks that it either implicitly trusts the certificate, or that it is verified and trusted by one of several Certificate Authorities (CAs) that it also implicitly trusts. Much more about this shortly. Note that the server is also allowed to require a certificate to prove the client ’s identity, but this typically only happens in very sensitive applications. 
5. Key Exchange - The encryption of the actual message data exchanged by the client and server will be done using a symmetric algorithm, the exact nature of which was already agreed during the Hello phase. A symmetric algorithm uses a single key for both encryption and decryption, in contrast to asymmetric algorithms that require a public/private key pair. Both parties need to agree on this single, symmetric key, a process that is accomplished securely using asymmetric encryption and the server ’s public/private keys.
   The client generates a random key to be used for the main, symmetric algorithm. It encrypts it using an algorithm also agreed upon during the Hello phase, and the server ’s public key (found on its SSL certificate). It sends this encrypted key to the server, where it is decrypted using the server ’s private key, and the interesting parts of the handshake are complete. The parties are sufficiently happy that they are talking to the right person, and have secretly agreed on a key to symmetrically encrypt the data that they are about to send each other. HTTP requests and responses can now be sent by forming a plaintext message and then encrypting and sending it. The other party is the only one who knows how to decrypt this message, and so Man In The Middle Attackers are unable to read or modify any requests that they may intercept. 
   AES and Wi-fi Protected Access 
   WPA2 replaced WPA. WPA2, which requires testing and certification by the Wi-Fi Alliance, implements the mandatory elements of IEEE 802.11i. In particular, it includes mandatory support for CCMP , an AES-based encryption mode with strong security.[6] Certification began in September, 2004; from March 13, 2006, WPA2 certification is mandatory for all new devices to bear the Wi-Fi trademark. 
   CCMP (CTR mode with CBC-MAC Protocol) 
   The protocol used by WPA2, based on the Advanced Encryption Standard (AES) cipher along with strong message authenticity and integrity checking that is significantly stronger in protection for both privacy and integrity than the RC4-based TKIP used by WPA. Among informal names are "AES" and "AES-CCMP". According to the 802.11n specification, this encryption protocol must be used to achieve the fast 802.11n high bitrate schemes, though not all implementations enforce this.[12] Otherwise, the data rate will not exceed 54 MBit/s. 