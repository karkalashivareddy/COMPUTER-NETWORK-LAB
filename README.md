# Computer Networks and Network Programming Lab

Skill record for the **Computer Networks and Network Programming** laboratory course, B.Tech. CSE, Trimester 5, KL University, Bachupally Campus, Hyderabad.

| | |
|---|---|
| **Name** | Karkala Shiva Reddy |
| **Roll Number** | 2520030105 |
| **Section** | 2 |
| **Course** | Computer Networks and Network Programming |
| **Department** | Computer Science and Engineering |
| **Academic Year** | 2026 |

---

## Skills

| Skill | Title | Focus | Report |
|:---:|---|---|---|
| 1 | Encapsulation Builder | Ethernet, IPv4 and TCP/UDP header overhead; payload efficiency | [CN-Skill-1.pdf](skill-1/CN-Skill-1.pdf) |

---

## Skill 1 — Encapsulation Builder

**Aim:** To capture network packets and understand how Ethernet, IP, and TCP/UDP headers are added during data transmission.

Packets were captured on the Wi-Fi interface with Wireshark for 30 seconds while browsing google.com, en.wikipedia.org and github.com. One TCP data packet and one UDP DNS query were inspected, and the header overhead and payload efficiency were calculated from the captured values.

| Result | TCP packet | UDP packet |
|---|---|---|
| Frame length | 1466 bytes | 74 bytes |
| Header overhead | 54 bytes | 42 bytes |
| Payload | 1412 bytes | 32 bytes |
| Payload efficiency | 96.32% | 43.24% |

The full report, including the observation table, calculations, answers to the review questions and conclusion, is available in [skill-1/CN-Skill-1.pdf](skill-1/CN-Skill-1.pdf).

---

## Repository Structure

```
COMPUTER-NETWORK-LAB/
├── README.md
└── skill-1/
    └── CN-Skill-1.pdf          # Final skill record
```

---

## Environment

| Item | Details |
|---|---|
| Operating System | Windows 11 Home Single Language (64-bit) |
| System | HP Laptop 15-fd0xxx, Intel Core i5-1334U, 16 GB RAM |
| Packet Analyser | Wireshark 4.6.9 (64-bit) |
| Capture Interface | Wi-Fi |
| Capture Date | 12 November 2026 |

---

## Notes

- The report follows the laboratory manual for Skill 1.
- All packet values in the report were recorded from a live capture on the local machine, not from sample data.
- The complete 30-second capture (28,663 packets) is kept locally and is not committed because of its size.
