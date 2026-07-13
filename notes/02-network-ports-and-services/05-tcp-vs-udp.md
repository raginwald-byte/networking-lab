# TCP vs UDP

## Why are there different network protocols?

When devices communicate over a network, they do not all have the same requirements.

Some applications require reliability, while others prioritize speed.

For this reason, two of the most common transport protocols are **TCP** and **UDP**.

## TCP (Transmission Control Protocol)

TCP is a reliable protocol.

Before sending data, it establishes a connection between the sender and the receiver.

TCP guarantees:

- Data is delivered.
- Data arrives in the correct order.
- Lost packets are retransmitted.

This makes TCP suitable for:

- Web browsing (HTTP / HTTPS)
- File transfers
- Emails

## UDP (User Datagram Protocol)

UDP is a faster and lighter protocol.

Unlike TCP, it does not establish a connection before sending data.

UDP does **not** guarantee:

- Packet delivery
- Packet order
- Packet retransmission

Because of this, UDP is ideal for applications where speed is more important than perfect reliability.

Examples include:

- Online gaming
- Voice calls
- Video streaming
- Live broadcasts

## Summary

TCP prioritizes reliability.

UDP prioritizes speed.

The choice depends on the needs of the application.