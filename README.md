<div align="center">

<svg width="100%" height="250" viewBox="0 0 1200 250" role="img" aria-label="Computer Networks engineering laboratory dashboard">
  <defs>
    <linearGradient id="cnBg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#08111f">
        <animate attributeName="stop-color" values="#08111f;#0d1e34;#08111f" dur="14s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#103b55">
        <animate attributeName="stop-color" values="#103b55;#0a2740;#103b55" dur="14s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="cnLine" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#22d3ee"/>
      <stop offset="50%" stop-color="#60a5fa"/>
      <stop offset="100%" stop-color="#22d3ee"/>
    </linearGradient>
  </defs>

  <rect width="1200" height="250" rx="20" fill="url(#cnBg)"/>

  <g stroke="#38bdf8" stroke-width="1.2" stroke-dasharray="6 9" opacity="0.45">
    <line x1="80" y1="212" x2="1120" y2="212">
      <animate attributeName="stroke-dashoffset" from="60" to="0" dur="3s" repeatCount="indefinite"/>
    </line>
    <line x1="120" y1="66" x2="380" y2="150"/>
    <line x1="380" y1="150" x2="700" y2="96"/>
    <line x1="700" y1="96" x2="1080" y2="170"/>
  </g>
  <g fill="#22d3ee" opacity="0.85">
    <circle cx="120" cy="66" r="5"/>
    <circle cx="380" cy="150" r="5"/>
    <circle cx="700" cy="96" r="5"/>
    <circle cx="1080" cy="170" r="5"/>
  </g>
  <circle cy="212" r="4" fill="#a5f3fc">
    <animate attributeName="cx" values="80;1120" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.2;1;0.2" dur="7s" repeatCount="indefinite"/>
  </circle>

  <text x="60" y="92" font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="40" font-weight="700" fill="#f8fafc">COMPUTER NETWORKS</text>
  <text x="60" y="134" font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="26" font-weight="500" fill="#7dd3fc">Packet-Level Engineering &amp; Measurement Lab</text>
  <text x="60" y="166" font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="15" fill="#cbd5e1">Encapsulation · Multi-point capture · Queueing · Latency percentiles · BDP</text>

  <rect x="60" y="184" height="4" rx="2" fill="url(#cnLine)">
    <animate attributeName="width" values="0;470" dur="2.4s" fill="freeze"/>
  </rect>

  <circle cx="1000" cy="52" r="6" fill="#34d399">
    <animate attributeName="opacity" values="1;0.25;1" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="1016" y="58" font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="15" font-weight="600" fill="#6ee7b7">ALL MODULES VERIFIED</text>
  <text x="1000" y="86" font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="13" fill="#94a3b8">4 / 4 evidence packages</text>
</svg>

</div>

<div align="center">

![Ubuntu](https://img.shields.io/badge/OS-Ubuntu%20WSL2-2f6fed?style=for-the-badge&logo=linux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Capture-Wireshark%204.6-1677c8?style=for-the-badge&logo=wireshark&logoColor=white)
![tshark](https://img.shields.io/badge/CLI-tshark%204.6-0f766e?style=for-the-badge)
![iperf3](https://img.shields.io/badge/Traffic-iperf3%203.20-7c3aed?style=for-the-badge)
![tc](https://img.shields.io/badge/Emulation-tc%20netem%20%7C%20tbf-b45309?style=for-the-badge)
![Bash](https://img.shields.io/badge/Automation-Bash-4eaa25?style=for-the-badge&logo=gnubash&logoColor=white)
![PDF](https://img.shields.io/badge/Reports-4%20PDFs-b31b1b?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)
![Status](https://img.shields.io/badge/Status-production%20review-16a34a?style=for-the-badge)

</div>

---

## Executive View

A compact, engineering-oriented body of work on **how packets actually behave** — header overhead, TTL decay, bottleneck queueing, latency distributions and bandwidth-delay product. Each module is a self-contained evidence package: controlled topology, exact command transcript, live terminal output, Wireshark dissection and a measured observation table. The dashboard presents results and workflows; identity and coursework metadata live only inside the versioned reports.

<div align="center">

<svg width="100%" viewBox="0 0 900 210" role="img" aria-label="Module verification coverage">
  <text x="20" y="26" font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="16" font-weight="600" fill="#e2e8f0">EVIDENCE COVERAGE</text>
  <g font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="13" fill="#94a3b8">
    <text x="20" y="62">Encapsulation / header dissection</text>
    <text x="20" y="102">Three-point capture / path analysis</text>
    <text x="20" y="142">Queueing curve / Little's Law</text>
    <text x="20" y="182">Percentiles / BDP / buffer sizing</text>
  </g>
  <g>
    <rect x="360" y="48" width="500" height="16" rx="8" fill="#1e293b"/>
    <rect x="360" y="48" height="16" rx="8" fill="#22d3ee">
      <animate attributeName="width" from="0" to="500" dur="1.5s" begin="0.1s" fill="freeze"/>
    </rect>
    <rect x="360" y="88" width="500" height="16" rx="8" fill="#1e293b"/>
    <rect x="360" y="88" height="16" rx="8" fill="#38bdf8">
      <animate attributeName="width" from="0" to="500" dur="1.5s" begin="0.25s" fill="freeze"/>
    </rect>
    <rect x="360" y="128" width="500" height="16" rx="8" fill="#1e293b"/>
    <rect x="360" y="128" height="16" rx="8" fill="#60a5fa">
      <animate attributeName="width" from="0" to="500" dur="1.5s" begin="0.4s" fill="freeze"/>
    </rect>
    <rect x="360" y="168" width="500" height="16" rx="8" fill="#1e293b"/>
    <rect x="360" y="168" height="16" rx="8" fill="#818cf8">
      <animate attributeName="width" from="0" to="500" dur="1.5s" begin="0.55s" fill="freeze"/>
    </rect>
  </g>
  <g font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="13" font-weight="700" fill="#a5f3fc">
    <text x="872" y="62">100%</text>
    <text x="872" y="102">100%</text>
    <text x="872" y="142">100%</text>
    <text x="872" y="182">100%</text>
  </g>
</svg>

</div>

---

## Modules

| ID | Engineering module | Investigation | Key measured result | Evidence |
|:---:|---|---|---|---|
| 01 | Encapsulation Builder | Ethernet / IPv4 / TCP-UDP header overhead and payload efficiency | TCP **96.32%** payload efficiency (1466 B frame, 54 B headers); UDP **43.24%** (74 B frame, 42 B headers) | [Report](SKILL/CN-Skill-1.pdf) · Wireshark dissections |
| 02 | Three-Point Capture | TTL decay, path delay and payload recovery across sender → router → receiver | TTL **64 → 64 → 63**; SYN gap **20.09 ms** vs 20 ms configured; five-line message recovered from TCP payload | [Report](SKILL/CN-Skill-2.pdf) · tshark + mtr + Wireshark |
| 03 | Queueing Curve & Little's Law | TBF bottleneck, knee point, buffer limits and `L = λ × W` | Knee at **5 Mbps**; loaded RTT **86.6–101 ms**; `L = 50.87 pkts` vs measured backlog **50.4 pkts** | [Report](SKILL/CN-Skill-3.pdf) · iperf3 + tc + Wireshark |
| 04 | Percentiles, BDP & Buffer Analysis | RTT distribution, iperf3 throughput and bandwidth-delay product | Mean **20.408 ms**, p95 **20.800 ms**, p99 **20.901 ms**; **96.11 / 96.57 Mbps**; BDP **≈245 KB** mean, **≈250 KB** p95 | [Report](SKILL/CN-Skill-4.pdf) · ping + iperf3 + Wireshark |

---

## Certifications

**Cisco Networking Academy** · KL University Hyderabad · Shiva Reddy Karkala · completed 20 Nov 2026

| # | Course | Cert ID | Evidence |
|:---:|---|---|---|
| 01 | CCNA: Introduction to Networks | `74b34be8-94ad-421a-8f97-5884afeb11ef` | [Certificate](certificates/CCNA-Introduction-to-Networks.pdf) |
| 02 | CCNA: Switching, Routing, and Wireless Essentials | `cea07609-f610-4e2f-ae91-1d81cb26e5a8` | [Certificate](certificates/CCNA-Switching-Routing-and-Wireless-Essentials.pdf) |
| 03 | CCNA: Enterprise Networking, Security, and Automation | `430bbf6f-619f-4086-8254-50cee53cd3b0` | [Certificate](certificates/CCNA-Enterprise-Networking-Security-and-Automation.pdf) |

Full index and file-integrity hashes: [`certificates/README.md`](certificates/README.md).

---

## Measured Signals

<div align="center">

<svg width="100%" viewBox="0 0 900 200" role="img" aria-label="Key measured network signals">
  <g font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="13" fill="#cbd5e1">
    <text x="20" y="36">TCP payload efficiency</text>
    <text x="20" y="80">UDP payload efficiency</text>
    <text x="20" y="124">iperf3 throughput / 100 Mbit link</text>
    <text x="20" y="168">Evidence verification</text>
  </g>
  <g>
    <rect x="330" y="22" width="500" height="18" rx="9" fill="#1e293b"/>
    <rect x="330" y="22" height="18" rx="9" fill="#22d3ee">
      <animate attributeName="width" from="0" to="482" dur="1.8s" begin="0.2s" fill="freeze"/>
    </rect>
    <rect x="330" y="66" width="500" height="18" rx="9" fill="#1e293b"/>
    <rect x="330" y="66" height="18" rx="9" fill="#f59e0b">
      <animate attributeName="width" from="0" to="216" dur="1.8s" begin="0.35s" fill="freeze"/>
    </rect>
    <rect x="330" y="110" width="500" height="18" rx="9" fill="#1e293b"/>
    <rect x="330" y="110" height="18" rx="9" fill="#34d399">
      <animate attributeName="width" from="0" to="483" dur="1.8s" begin="0.5s" fill="freeze"/>
    </rect>
    <rect x="330" y="154" width="500" height="18" rx="9" fill="#1e293b"/>
    <rect x="330" y="154" height="18" rx="9" fill="#818cf8">
      <animate attributeName="width" from="0" to="500" dur="1.8s" begin="0.65s" fill="freeze"/>
    </rect>
  </g>
  <g font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="13" font-weight="700" fill="#e2e8f0">
    <text x="842" y="36">96.3%</text>
    <text x="842" y="80">43.2%</text>
    <text x="842" y="124">96.6%</text>
    <text x="842" y="168">100%</text>
  </g>
</svg>

</div>

---

## Implementation Stack

| Layer | Components |
|---|---|
| Packet inspection | Wireshark 4.6.9 GUI, tshark 4.6.4 CLI, display/capture filters |
| Traffic generation | iperf3 3.20 (TCP/UDP), nc, ping, mtr |
| Network emulation | `ip netns`, veth pairs, `tc netem`, `tc tbf`, `sysctl` forwarding |
| Host environment | Ubuntu on WSL2, Bash automation, Linux kernel 6.18.x |
| Analysis | Payload decoding, TTL/timestamp extraction, RTT percentiles, Little's Law, BDP |
| Evidence packaging | A4 PDF reports with aligned step screenshots and measured observation tables |

---

## Command Workflows

<details>
<summary><b>02 · Three-point capture and path analysis</b></summary>

```bash
sudo apt install -y tshark iproute2 netcat-openbsd mtr-tiny

ip netns add host1; ip netns add router; ip netns add host2
ip link add veth-h1 type veth peer name veth-r1
ip link add veth-r2 type veth peer name veth-h2
ip link set veth-h1 netns host1
ip link set veth-r1 netns router
ip link set veth-r2 netns router
ip link set veth-h2 netns host2

ip netns exec host1 ip addr add 10.0.1.1/30 dev veth-h1
ip netns exec router ip addr add 10.0.1.2/30 dev veth-r1
ip netns exec router ip addr add 10.0.2.1/30 dev veth-r2
ip netns exec host2 ip addr add 10.0.2.2/30 dev veth-h2
ip netns exec router sysctl -w net.ipv4.ip_forward=1

ip netns exec router tc qdisc replace dev veth-r2 root netem delay 20ms loss 1%
tshark -i veth-h1 -w /tmp/cap1.pcap
tshark -i veth-r1 -w /tmp/cap2.pcap
tshark -i veth-h2 -w /tmp/cap3.pcap

ip netns exec host2 nc -l 1234
ip netns exec host1 nc 10.0.2.2 1234

tshark -r /tmp/cap2.pcap -Y "tcp.port == 1234" -T fields -e tcp.payload
ip netns exec host1 mtr --report --report-cycles 5 10.0.2.2
```

</details>

<details>
<summary><b>03 · Bottleneck queueing and Little's Law</b></summary>

```bash
sudo apt install -y iperf3 tshark wireshark iproute2

ip netns exec router tc qdisc replace dev veth-r2 root \
  tbf rate 5mbit burst 32kb limit 64kb

ip netns exec host2 iperf3 -s -D
ip netns exec host1 iperf3 -c 10.0.2.2 -u -b 5M  -l 1200 -t 8 -i 1
ip netns exec host1 iperf3 -c 10.0.2.2 -u -b 10M -l 1200 -t 8 -i 1

tshark -i veth-r2 -f udp -w queueing_capture.pcap   # display filter: udp
ip netns exec router tc -s qdisc show dev veth-r2
# L = lambda x W  ->  50.87 pkts computed vs 50.4 pkts measured
```

</details>

<details>
<summary><b>04 · Latency percentiles and bandwidth-delay product</b></summary>

```bash
sudo apt install -y iperf3 tshark iproute2

ip netns exec host1 tc qdisc replace dev veth-h1 root netem delay 10ms rate 100mbit
ip netns exec host2 tc qdisc replace dev veth-h2 root netem delay 10ms rate 100mbit

ip netns exec host2 ping -c 200 -i 0.2 10.0.1.1      # RTT percentiles
tshark -i veth-h2 -f icmp -w traffic.pcap            # display filter: icmp

ip netns exec host1 iperf3 -s -D
ip netns exec host2 iperf3 -c 10.0.1.1 -t 30 -i 1       # forward
ip netns exec host2 iperf3 -c 10.0.1.1 -R -t 30 -i 1     # reverse
# BDP = bandwidth x RTT / 8  ->  ~245 KB mean, ~250 KB p95
```

</details>

---

## Verification Record

| Check | Result |
|---|:---:|
| Real Ubuntu/WSL terminal captures (install, setup, live output) | Passed |
| Real Wireshark GUI captures with correct capture file and display filter | Passed |
| Every figure matched to its source screenshot (perceptual hash, distance 0) | Passed |
| Step/command above each figure, caption below, zero text-image overlap | Passed |
| Enlarged institutional banner: one consistent 322.5 pt logo per report | Passed |
| Page footers, metadata correctness, no sign-off/date blocks | Passed |

<div align="center">

<svg width="360" height="54" role="img" aria-label="Verification status">
  <rect width="360" height="54" rx="12" fill="#052e2b"/>
  <circle cx="30" cy="27" r="8" fill="#34d399">
    <animate attributeName="opacity" values="1;0.35;1" dur="2.4s" repeatCount="indefinite"/>
  </circle>
  <path d="M26 27 l3 4 l6 -8" fill="none" stroke="#052e2b" stroke-width="2.5"/>
  <text x="52" y="33" font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="18" font-weight="700" fill="#6ee7b7">VERIFIED EVIDENCE PACKAGE</text>
</svg>

</div>

---

## Repository Layout

```text
COMPUTER-NETWORK-LAB/
├── README.md                       # animated engineering dashboard
├── assets/
│   └── klh_header.jpeg             # institutional banner embedded in reports
├── certificates/
│   ├── README.md                   # credential index and SHA-256 hashes
│   ├── CCNA-Introduction-to-Networks.pdf
│   ├── CCNA-Switching-Routing-and-Wireless-Essentials.pdf
│   └── CCNA-Enterprise-Networking-Security-and-Automation.pdf
└── SKILL/
    ├── CN-Skill-1.pdf              # encapsulation builder
    ├── CN-Skill-2.pdf              # three-point capture
    ├── CN-Skill-3.pdf              # queueing curve & Little's Law
    └── CN-Skill-4.pdf              # percentiles, BDP & buffer analysis
```

> Raw packet captures are intentionally kept outside version control because of file size; final reports, the shared banner asset and the CCNA certificate PDFs are tracked. No synthetic terminal panels are used anywhere in the evidence set.

---

<div align="center">

**Network Engineering Reference · Computer Networks & Network Programming**

<sub>Dashboard generated for technical review — module reports contain the complete command-level evidence.</sub>

</div>
