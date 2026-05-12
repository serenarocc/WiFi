# Performance Evaluation in Ethernet and Wi-Fi Scenarios

The objective of this study is to evaluate the efficiency of wireless and physical network links by comparing theoretical predictions with experimental results across various LAN configurations.

---

##  Project Description
The study focuses on measuring and analyzing **Goodput**, the speed at which useful data is received at the application layer. 
We compare **Ethernet** (IEEE 802.3) and **Wi-Fi** (IEEE 802.11ac) using both **TCP** and **UDP** protocols to understand how protocol overhead and wireless-specific limitations (like half-duplex medium and channel congestion) affect performance.

## Tested Scenarios
1.  **Both Ethernet**: Both Host A and Host B are connected via GbE cables to the router.
2.  **Both Wi-Fi**: Both hosts are linked to the same wireless channel.
3.  **Mixed Scenario**: Host A is connected via Ethernet, while Host B is connected via Wi-Fi.

---

## Tools Used
* **iperf3**: Used to generate traffic and measure goodput fluctuations.
* **Wireshark**: Used for packet analysis, monitoring TCP window scaling, RTT, and I/O graphs.
* **Python**: Custom scripts were used to automate multiple test runs (10 iterations per test) and collect statistical data.

---

This project was developed as part of the **Wireless and Device-to-Device Communication Security** course at **Politecnico di Torino**, with my colleagues.
