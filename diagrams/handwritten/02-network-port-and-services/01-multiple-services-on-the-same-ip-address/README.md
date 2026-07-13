# Multiple Services on the Same IP Address

## Description

This handwritten diagram illustrates how multiple network services can run simultaneously on a single device using the same IP address.

Each service listens on a different network port, allowing the operating system to deliver incoming data to the correct application.

Examples shown in the diagram:

- HTTP → Port 80
- HTTPS → Port 443
- Minecraft Server → Port 25565

This demonstrates that one computer can act as several servers at the same time, provided that each service uses a different port.

## Key concepts

- One IP address can host multiple services.
- Each service is identified by a unique port.
- The operating system directs incoming traffic to the correct application.
- Ports allow multiple applications to communicate without interfering with each other.

---

## Related lesson

[Why Network Ports?](../../../../notes/02-network-ports-and-services/01-why-network-ports.md)