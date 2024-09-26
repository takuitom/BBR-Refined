This repository has been created for experimenting the BBR-R scheme proposed in "BBR-R: Improving BBR’s RTT Fairness by Dynamically Adjusting Delay Detection Intervals" in Linux Kernel. The article is available at: https://link.springer.com/chapter/10.1007/978-3-031-57840-3_7

Just replace the existing tcp_bbr.c in /usr/src/.../net/ipv4/. make and make install for the directory. reboot the system. Change the default Congestion Algorithm to bbrr

For any questions, please contact hanzeweitakui@outlook.com
