# Task 7.1 — Explain Network Concepts

-LAN (Local Area Network):
A LAN connects computers and devices within a small geographical area, such as a home, office or laboratory.
Example: A home Wi-Fi network.

-MAN (Metropolitan Area Network):
A MAN connects networks across a city or a large campus area.
Example: A network connecting different buildings across a university campus

-WAN (Wide Area Network):
A WAN connects computers and networks across large geographical distances
Example: The Internet

-DNS (Domain Name System):
DNS translates human-readable domain names into IP addresses that computers use to locate servers
Example: Resolving `google.com` to an IP address.

-Router:
A router connects different networks and forwards data packets towards their destination.
Example: A home Wi-Fi router connecting devices to the Internet.

-Protocol:
A protocol is a set of rules that defines how devices communicate and exchange data
Example: HTTP, HTTPS and TCP

-Packet Switching:
Packet switching is a method in which data is divided into smaller units called packets and transmitted across a network.
Example: Sending a message over the Internet

-Client-Server
In this model, a client requests data or a service, and a server processes the request and provides a response
Example: A web browser requesting a webpage from a web server


# Task 7.2 — Observe Network Information

A. Connectivity Test

Command used:
`ping -c 4 google.com`

Observations:
- Packets transmitted: 4
- Packets received: 4
- Packet loss: 0%
- Average response time: 32.141 ms
- Minimum response time: 30.861 ms
- Maximum response time: 33.350 ms

My understanding:
A connectivity test checks whether a computer can reach a server over a network. The ping command sends test packets and measures the time taken to receive responses. Zero packet loss indicates that all four packets received responses.


# Task 7.3 — What Happens When You Open a Website?

1. User enters a website name: I type a website address, such as `google.com`, into the browser. The browser acts as a client that requests information.

2. DNS lookup: The browser uses DNS to find the IP address associated with the domain name.

3. Connection is established: The computer sends a request through its network. The router helps forward the data towards the destination server.

4. Request reaches the server: The browser sends an HTTP or HTTPS request using these communication protocols. The server receives and processes the request.

5. Server sends a response: The server sends the requested webpage data back to the client in packets.

6. Browser processes the response: The browser interprets the received HTML, CSS and JavaScript files and prepares the webpage.

7. Website is displayed: The browser displays the webpage so the user can view and interact with it.