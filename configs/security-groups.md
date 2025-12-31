<b>Account A (OnPrem)</b>

Security Group Name: VPN-Gateway-SG

<b>Rules:</b>

SSH (22): From MyIp

UDP 500: From 0.0.0.0/0 (For IKE/VPN tunnel).

UDP 4500: From 0.0.0.0/0 (For NAT-Traversal).

All ICMP - IPv4: From 10.2.0.0/16
