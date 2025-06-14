# Tracking of Default Settings Vulnerabilities of Home Router Features in the journal version

This repo tracks new vulnerabilities discovered in our work<sup>[1]</sup>, which is a extended version of our AsiaCCS paper<sup>[2]</sup>.

30 vulnerabilities found in our AsiaCCS paper are recorded in [AsiaCCS2024_vul_report](https://github.com/YjjNJUPT/AsiaCCS2024_vul_report).
We find 59 new vulnerabilities in this extended version, including vulnerable to ARP spoofing, vulnerable to CSRF, and TLS misuse in DDNS service.

We have reported all of confirmed vulnerabilities to manufacturers. Only TP-Link and Xiaomi accepted and fixed TLS misuse in DDNS service. Other vulnerabilities are rejected or not responded by manufacturers.
We will report them to CVE/CNVD later.

The status of these new vulnerabilities is listed below.

Vulnerability type  |  Manufacturer  |  Status
  ----              |  ----          |  ----
Vulnerable to ARP spoofing | ASUS(3) and NETGEAR(5) | They don't think it's a vulnerability because users can use HTTPS (default disabled) to access router to avoid it.
Vulnerable to ARP spoofing | H3C | H3C doesn't think it's a vulnerability because the risk is limited.
Vulnerable to ARP spoofing | Linksys(4) | End of Life
Vulnerable to ARP spoofing | Netcore and Tenda | No vulnerability submission channel
Vulnerable to CSRF         | Tenda | No vulnerability submission channel
TLS misuse in DDNS service (No-IP)  | D-Link(2) | No response
TLS misuse in DDNS service (No-IP)  | H3C and ZTE | They don't think it's a vulnerability because the risk is limited.
TLS misuse in DDNS service (No-IP)  | Linksys(4) | End of Life
TLS misuse in DDNS service (No-IP)  | NETGEAR(4) | PSV-2024-0096
TLS misuse in DDNS service (No-IP)  | Tenda(2) | No vulnerability submission channel
TLS misuse in DDNS service (No-IP)  | TP-Link(3) and Xiaomi(2) | Fixed
TLS misuse in DDNS service (DynDNS) | D-Link(3) and Ruijie | No response
TLS misuse in DDNS service (DynDNS)  | Linksys(5) | End of Life
TLS misuse in DDNS service (DynDNS)  | NETGEAR(4) | PSV-2024-0096
TLS misuse in DDNS service (DynDNS)  | Tenda(2) | No vulnerability submission channel
TLS misuse in DDNS service (DynDNS)  | TP-Link(3) and Xiaomi(2) | Fixed
TLS misuse in DDNS service (Oray)    | HUAWEI(2) | A known issue
TLS misuse in DDNS service (Oray)    | Xiaomi(2) | Fixed

[1] Junjian Ye, Xavier de Carné de Carnavalet, Lianying Zhao, Mengyuan Zhang, Lifa Wu, and Wei Zhang. Exposed by Default: A Security Analysis of Home Router Default Settings and Beyond. In IEEE Internet of Things Journal, vol. 12, no. 2, pp. 1182-1199, 2025.

[2] Junjian Ye, Xavier de Carné de Carnavalet, Lianying Zhao, Mengyuan Zhang, Lifa Wu, and Wei Zhang. Exposed by Default: A Security Analysis of Home Router Default Settings. In ACM Asia Conference on Computer and Communications Security (ASIA CCS ’24), July 1–5, 2024, Singapore, Singapore. ACM, NewYork, NY, USA, 17 pages. https://doi.org/10.1145/3634737.3637671
