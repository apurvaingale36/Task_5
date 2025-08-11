
# README – Network Packet Capture

## **Objective**

Capture live network packets, identify basic network protocols, and document findings.

## **Tools Used**

* **Wireshark** (free, open-source network protocol analyzer)
* **Kali Linux** environment

## **Procedure**

1. Installed and launched Wireshark.
2. Selected the active network interface (`eth0` in this example).
3. Began packet capture and generated traffic by:

   * Opening a web browser to visit example websites.
   * Running a `ping` command to `google.com`.
4. Stopped capture after \~1 minute.
5. Applied protocol filters in Wireshark (`dns`, `http`, `icmp`, `tcp`, etc.).
6. Identified at least three distinct protocols.
7. Saved capture as **network\_capture.pcapng**.
8. Wrote a short analysis report summarizing findings.

## **Deliverables**

* **network\_capture.pcapng** → The raw packet capture file.

## **Identified Protocols**

* **DNS (UDP/53)** → Resolving domain names to IP addresses.
* **HTTP (TCP/80)** → Browsing unencrypted websites.
* **ICMP** → Network connectivity testing (ping).

## **Notes**

* Capture file may contain additional protocols depending on background system activity.
* Ensure sensitive data is removed before sharing captures publicly.
* For deeper analysis, use Wireshark’s **Statistics → Protocol Hierarchy** and **Follow TCP Stream** features.


