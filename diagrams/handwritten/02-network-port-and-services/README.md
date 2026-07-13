# HTTPS Request on Port 443

## Description

This handwritten diagram illustrates how an HTTPS request travels from a local application to a remote web server.

It shows the different stages of the communication:

1. A local application sends a request.
2. The operating system forwards the request.
3. The request leaves the local network through the gateway.
4. It travels across the Internet.
5. The destination server receives the request on **port 443 (HTTPS)**.
6. The response is sent back to the original application.

## Key concepts

- Source application
- Operating system
- Gateway
- Internet
- Destination server
- HTTPS (Port 443)
- Return path

This diagram helped me understand that a network communication is defined by an **IP address**, a **port number**, and a **transport protocol**.

---

## Related lesson

[IP Address, Port and Protocol](../../../../notes/02-network-ports-and-services/06-ip-port-and-protocol.md)