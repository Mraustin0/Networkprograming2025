# portfolio นาย ภควัฒน์ สุขมณี 673380418-9 Sec 3
## Network Programming 2025

A weekly lab-based journey from classical sockets to future networks. Building one network agreement in Python every week—simple first, then fragile, then strange.

## Assignment

| Assigment | Link |
|---|------|
| 1 | [View](https://drive.google.com/file/d/1DB6wDfJv0-OfySo8MpbAQ1d7A_EFZdOH/view) |
| 2 | [View](https://drive.google.com/file/d/1o1Wlf1D5BoUm1e5vj_5ivEIzYGEgAnih/view) |
| 3 | [View](https://drive.google.com/file/d/1xtFVpb6kgQgHO_L7IVqPQdAcgPy1PxaH/view) |
| 4 | [View](https://drive.google.com/file/d/1MTq3fB63UxEuIErSeyKDjCp6hp4FETCr/view) |

## Lab

| Lab | Link |
|---|------|
| 1 | [View](https://drive.google.com/drive/folders/1lrjBh2rPB_R8hAyiQWnC_tRvXePCeC58) |
| 2 | [View](https://drive.google.com/drive/folders/1gKxVp7Msv1goAc-qVjaii3n9J7L3oZjL) |
| 3 | [View](https://docs.google.com/document/d/1b6seUDwDQGkblKG7FD6fHTNp6NhI96XA/edit#heading=h.aymmukz9s64c) |
| 4 | [View](https://drive.google.com/file/d/1vxzVsq9obQggzFQRCA72gQGBaqAcMBVb/view) |

## Final Project – LivingBioNetwork

[View Project](https://drive.google.com/drive/folders/1X2T8bJzwBWj4mMlwfqscObfP7YfmPsjm)

## Course Philosophy

Networks are not cables and boxes. **They are agreements under uncertainty.** You already know IP addressing and routing. Now we program behavior.

## Learning Path Overview

| Week | Topic | Type | Core Concepts |
|------|-------|------|---|
| 1 | Client–Server Communication (TCP Unicast) | BASIC | TCP sockets, bind, listen, accept, connect, request–response |
| 2 | UDP Communication (Connectionless Unicast) | BASIC | UDP sockets, datagrams, packet loss, no guarantees |
| 3 | Broadcast Communication | BASIC | LAN broadcast scope, discovery, service advertisement |
| 4 | Multicast Communication | BASIC | Group membership, multicast groups, selective delivery |
| 5 | Peer-to-Peer Networking | BASIC | Symmetric roles, dynamic ports, no central server |
| 6 | Ad-Hoc Networking (MANET Simulation) | BASIC | Neighbor discovery, routing, TTL, improvised networks |
| 7 | Store-and-Forward Communication | BASIC | Message queues, retry logic, persistent buffers |
| 8 | Opportunistic Routing | BASIC | Probability-based forwarding, encounter routing |
| 9 | Bio-Inspired Networking | ADVANCED | Pheromone routing, reinforcement learning, adaptive paths |
| 10 | Quantum-Inspired Networking | ADVANCED | No-cloning, one-time tokens, quantum-secure concepts |

## Implementation Checklist

### Completed Implementations
- [x] Week 1: TCP Client–Server (server.py, server_threaded.py, client.py)
- [x] Week 2: UDP Unicast (sender.py, receiver.py)
- [x] Week 3: UDP Broadcast (broadcaster.py, listener.py)
- [x] Week 4: UDP Multicast (sender.py, receiver.py)
- [x] Week 5: Peer-to-Peer (peer.py)
- [x] Week 6: MANET Phase-1 (node.py with random port support)
- [x] Week 7: Store-and-Forward Phase-1 (node.py, message_queue.py)

### In Progress / Planning
- [x] Week 8: Opportunistic Routing implementation
- [x] Week 9: Bio-Inspired Networking (pheromone routing)
- [x] Week 10: Quantum-Inspired Networking (conceptual)

### Codebase Structure

```
networkprogramming2025/
├── week01-tcp-client-server-basic/
│   ├── server.py                 (TCP server)
│   ├── server_threaded.py        (Multi-threaded server)
│   ├── client.py                 (TCP client)
│   ├── config.py                 (Configuration)
│   ├── logger.py                 (Logging)
│   └── test_concurrent.py        (Unit tests)
├── week02-udp-unicast-basic/
│   ├── sender.py                 (UDP sender)
│   ├── receiver.py               (UDP receiver)
│   └── config.py
├── week03-udp-broadcast-basic/
│   ├── broadcaster.py            (Broadcast sender)
│   ├── listener.py               (Broadcast receiver)
│   └── config.py
├── week04-udp-multicast-basic/
│   ├── sender.py                 (Multicast sender)
│   ├── receiver.py               (Multicast receiver)
│   └── config.py
├── week05-peer-to-peer-basic/
│   ├── peer.py                   (P2P node)
│   └── config.py
├── week06-manet-basic/
│   ├── node.py                   (MANET node)
│   ├── config.py
│   └── phase-1-random-port/      (Random port variant)
│       ├── node.py
│       └── config.py
├── week07-store-forward-basic/
│   ├── node.py                   (Store-forward node)
│   ├── message_queue.py          (Queue implementation)
│   ├── config.py
│   └── phase-1-random-port/      (Random port variant)
│       ├── node.py
│       ├── message_queue.py
│       └── config.py
└── workshop/
    ├── Curriculum- Network Programming 2025.md
    └── [Lab guides and research notes]
```

## Key Learning Outcomes by Week

### WEEK 1 – TCP Unicast
- Understand TCP client–server architecture
- Implement blocking socket communication
- Relate TCP reliability to application behavior
- **Traits**: Structured thinking, protocol discipline

### WEEK 2 – UDP Unicast
- Compare TCP vs UDP trade-offs
- Implement connectionless communication
- Observe and handle packet loss behavior
- **Traits**: Risk awareness, performance analysis

### WEEK 3 – Broadcast
- Understand LAN broadcast scope
- Implement discovery mechanisms
- **Real-world usage**: DHCP, service discovery

### WEEK 4 – Multicast
- Join multicast groups
- Differentiate multicast vs broadcast
- Opt-in group communication
- **Real-world usage**: Video streaming, pub/sub

### WEEK 5 – Peer-to-Peer
- Build symmetric network roles
- Handle dynamic ports
- **Real-world usage**: File sharing, decentralized systems

### WEEK 6 – Ad-Hoc Networking (MANET)
- Simulate neighbor discovery
- Implement forwarding with TTL
- **Extension**: AODV/OLSR concepts

### WEEK 7 – Store-and-Forward
- Implement message queues
- Handle retry logic
- **Extension**: Persistent storage, delay-tolerant networks

### WEEK 8+ – Advanced Topics
- Opportunistic routing (probability-based)
- Bio-inspired networking (pheromone routing)
- Quantum-inspired concepts (one-time tokens, secure messaging)

## Getting Started

1. Navigate to any `week*` directory
2. Configure your environment in `config.py`
3. Run server/sender in one terminal
4. Run client/receiver in another terminal
5. Observe the network behavior

Example (Week 1):
```bash
python server.py
python client.py
```
