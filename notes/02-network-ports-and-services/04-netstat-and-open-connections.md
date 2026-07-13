# netstat and Active Connections

## What is `netstat`?

`netstat` is a command-line tool that displays active network connections on a computer.

It provides useful information about:

- Active TCP and UDP connections
- Listening ports
- Local and remote IP addresses
- Process IDs (PIDs)

## Command used

```cmd
netstat -ano
```

### Options

- **-a** → Displays all active connections and listening ports.
- **-n** → Displays addresses and ports in numerical form.
- **-o** → Displays the Process ID (PID) associated with each connection.

## Why is this command useful?

The `netstat` command helps identify:

- Which ports are currently in use.
- Which remote devices the computer is communicating with.
- Which process is using a specific network connection.

It is commonly used for network troubleshooting and basic cybersecurity analysis.

## Summary

`netstat -ano` provides a detailed view of the current network activity on a computer and is an essential tool for understanding how applications communicate over the network.