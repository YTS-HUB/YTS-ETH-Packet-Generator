<div align="center">

# YTS ETH Packet Generator

### Every header field under your control

**Ethernet II · VLAN 802.1Q · IPv4 · UDP · TCP · ICMP**

Craft and transmit custom Ethernet frames — burst or continuous, fixed or random size —
and watch throughput and errors live.
Precision traffic testing without the four-figure commercial licence.

<br>

[![Download](https://img.shields.io/badge/Download-yts--hub.com-0FB89B?style=for-the-badge&logo=windows&logoColor=white)](https://yts-hub.com/packet-generator/)
[![Website](https://img.shields.io/badge/Website-yts--hub.com-40D9EE?style=for-the-badge&logoColor=white)](https://yts-hub.com/)

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20%2864--bit%29-0FB89B?style=flat-square)
![Layers](https://img.shields.io/badge/layers-L2%20%2B%20L3-6E5DF6?style=flat-square)
![Install](https://img.shields.io/badge/install-no%20extra%20runtimes-F7AB00?style=flat-square)

<br>

<img width="560" alt="YTS ETH Packet Generator — header configuration above a live transmit/receive monitor" src="screenshots/packet-main-window.png">

<sub>Configuration and the live monitor in one window — shown in dark mode</sub>

</div>

---

## What it is

**YTS ETH Packet Generator** is a desktop tool for Windows that builds Ethernet frames field by
field and puts them on the wire — then measures what happened.

Set the source and destination MAC, add a VLAN tag, override any IPv4 header field, pick UDP, TCP or
ICMP, type the payload straight in hex, and transmit continuously or in precise bursts at a target
rate. The built-in monitor shows packets/sec, throughput, drops and a live Tx/Rx graph while it runs,
so you don't need a separate analyzer to see the result.

> Download, screenshots and full details:
> **https://yts-hub.com/packet-generator/**

---

## Highlights

|  | |
|---|---|
| 🔧 **Full Layer 2 control** | Source and destination MAC, EtherType, and 802.1Q VLAN tagging with priority and CFI. |
| 🌐 **Full IPv4 control** | Source and destination IP, ToS/DSCP, TTL and protocol — override any field. |
| 📦 **UDP / TCP / ICMP** | Transport payloads for the three protocols that matter most in network validation. |
| ✎ **Hex payload editor** | Type the payload byte by byte. Build malformed or edge-case frames on purpose. |
| 💥 **Continuous & burst** | Stream indefinitely or fire precise bursts, at a fixed or ranged bit rate. |
| 📏 **Fixed & random sizes** | Exact-length frames, or randomised 64–1518 to emulate mixed real-world traffic. |
| 📊 **Live traffic monitor** | Tx/Rx packets, bytes, bps, average PPS, dropped packets and a rate-over-time graph. |
| 🎯 **Repeatable** | Save a configuration and reproduce identical test conditions — essential for regression work. |

---

## Four steps to first frame

| | | |
|:--:|---|---|
| **01** | **Select your interface** | Pick the exact adapter that will transmit your frames. |
| **02** | **Configure the headers** | MAC, VLAN, IP, protocol, ports — set every field you need to control. |
| **03** | **Set size & rate** | Fixed or random size, continuous or burst, at your target bit rate. |
| **04** | **Start & monitor** | Hit transmit and watch throughput, PPS and drops in real time. |

---

## The real application

<table>
<tr>
<td width="50%"><img alt="Ethernet, VLAN, IPv4 and protocol header fields with packet size and rate configuration" src="screenshots/packet-headers.png"></td>
<td width="50%"><img alt="Packet Review and Edit pane showing the assembled frame in raw hex" src="screenshots/packet-hex-editor.png"></td>
</tr>
<tr>
<td align="center"><sub><b>Header configuration</b> · L2, VLAN, IPv4, transport and packet config in one pane</sub></td>
<td align="center"><sub><b>Hex view & editor</b> · review the assembled frame, or edit it byte by byte</sub></td>
</tr>
</table>

<div align="center">
<img width="560" alt="Live monitor with Tx/Rx counters and a rate-over-time graph during a continuous transmission" src="screenshots/packet-monitor.png">

<sub><b>Live monitor</b> · Tx/Rx packets, bytes, bps, average PPS, dropped packets and a rate-over-time graph</sub>
</div>

---

## What engineers test with it

| | |
|---|---|
| 🏷️ **VLAN & QoS handling** | Send tagged frames with specific DSCP/ToS markings and verify your switches classify, remark and prioritise exactly as designed. |
| 🧱 **Firewall & ACL checks** | Craft the exact 5-tuple a rule should match — then the one it shouldn't — and prove the policy behaves before an auditor asks. |
| 📉 **Throughput & storms** | Burst at line rate to find where a link saturates, when buffers overflow, and whether storm-control kicks in at the threshold. |
| 🧪 **Malformed frames** | Build undersized, oversized or deliberately wrong frames in the hex editor — the tests vendors hope you never run. |
| 🔬 **Embedded & QA** | Drive a device under test with reproducible traffic, then diff the counters run over run. |

---

## Full feature list

<details>
<summary><b>Packet generation</b></summary>

Custom Ethernet frame builder · manual packet crafting · configurable payload generation ·
continuous transmission · burst transmission · high-speed traffic generation · packet replay ·
fixed or random packet size (64–1518) · fixed or ranged bit rate
</details>

<details>
<summary><b>Protocol support</b></summary>

Ethernet II · VLAN (802.1Q, with priority and CFI) · IPv4 · IPv6 · TCP · UDP · ICMP · ARP
</details>

<details>
<summary><b>Traffic analysis</b></summary>

Real-time packet monitoring · Tx/Rx packet and byte counters · Tx/Rx bit-rate and average PPS ·
dropped-packet count · run-time counter · rate-over-time graph · HEX packet visualisation ·
ASCII payload view · timestamped logging · packet inspection tools
</details>

<details>
<summary><b>Productivity</b></summary>

Saved packet templates · configurable transmission profiles · session logging · multi-tab
interface · dark mode UI · high-performance renderer · network interface selection
</details>

<details>
<summary><b>Use cases</b></summary>

Network diagnostics · protocol validation · embedded device testing · firewall and ACL testing ·
traffic simulation · security research · QA and stress testing
</details>

---

## Technical specifications

| | |
|---|---|
| **OS** | Windows 10 / 11 (64-bit) |
| **Layers** | Ethernet II (L2), IPv4 (L3) |
| **Transport** | UDP, TCP, ICMP |
| **Transmission** | Continuous & burst · fixed or random size · configurable bit rate |
| **Payload** | Hex editor for full byte-level control |
| **Monitoring** | Real-time packets/sec, throughput, drops and Tx/Rx graph |
| **Install** | Standard installer — no additional runtimes |
| **Licence** | Currently free for personal and commercial use |

---

## Download

<div align="center">

### [⬇ Get the ETH Packet Generator](https://yts-hub.com/packet-generator/)

**https://yts-hub.com/packet-generator/**

The installer and full product details are on the product page.

</div>

---

## Responsible use

This tool transmits raw frames on a live network. **Use it only on infrastructure you own or have
written permission to test.** Crafted traffic can disrupt production networks, trip storm-control,
and will look like an attack to anything monitoring the segment — run it on a lab link or an agreed
maintenance window.

---

## FAQ

<details>
<summary><b>Which headers and protocols can I control?</b></summary>

Full Ethernet II (Layer 2) header control including MAC addressing and 802.1Q VLAN tagging, plus the
IPv4 (Layer 3) header — source/destination IP, ToS, TTL — with UDP, TCP and ICMP transport payloads
and a hex editor for byte-level payload control.
</details>

<details>
<summary><b>Can I use it for security research?</b></summary>

Yes — crafting frames to analyse protocol behaviour on networks you're authorised to test is exactly
what it's for. As with any testing tool, only use it on infrastructure you own or have permission to
test.
</details>

<details>
<summary><b>Does it work on Wi-Fi adapters?</b></summary>

It transmits on the network interface you select. Wired Ethernet adapters give the most faithful
Layer 2 control; wireless adapters and their drivers may rewrite or restrict raw frames.
</details>

<details>
<summary><b>How fast can it transmit?</b></summary>

You set a target bit rate — fixed, or ranged between a minimum and maximum. Actual throughput
depends on your adapter, driver and the link. The monitor reports the rate it genuinely achieved,
along with any dropped packets.
</details>

<details>
<summary><b>Is the source code here?</b></summary>

No — this repository is the public home for documentation, screenshots and issue reports. The
application itself is a closed-source Windows tool distributed from
[yts-hub.com](https://yts-hub.com/packet-generator/).
</details>

---

## More from YTS-Hub

| | |
|---|---|
| 🖥 **[YTS Terminal Manager](https://yts-hub.com/terminal-manager/)** | SSH, Telnet, Serial, SFTP, FTP, SCP and RDP in one Windows app — with a built-in AI assistant, Python automation and an embedded server stack. |
| 🔌 **[Serial Traffic Generator](https://yts-hub.com/serial-generator/)** | Stress-test RS-232/RS-485 links with patterns, error injection and a visual comparator. |

---

<div align="center">

**[yts-hub.com](https://yts-hub.com/)** · *Master the Network*

Free professional network tools for Windows. Built by an engineer, for engineers.

Questions or bugs? [Open an issue](../../issues) or use the
[contact page](https://yts-hub.com/contact/).

</div>
