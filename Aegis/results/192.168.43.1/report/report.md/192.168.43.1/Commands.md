```bash
nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/routersploit/results/192.168.43.1/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/routersploit/results/192.168.43.1/scans/xml/_quick_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/routersploit/results/192.168.43.1/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/routersploit/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/routersploit/results/192.168.43.1/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/routersploit/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml" 192.168.43.1

dig -p 53 -x 192.168.43.1 @192.168.43.1

dig AXFR -p 53 @192.168.43.1

nmap -vv --reason -Pn -T4 -sV -p 53 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/routersploit/results/192.168.43.1/scans/tcp53/tcp_53_dns_nmap.txt" -oX "/home/eni9ma/routersploit/results/192.168.43.1/scans/tcp53/xml/tcp_53_dns_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/routersploit/results/192.168.43.1/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/routersploit/results/192.168.43.1/scans/xml/_quick_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/routersploit/results/192.168.43.1/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/routersploit/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/routersploit/results/192.168.43.1/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/routersploit/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_quick_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml" 192.168.43.1

dig -p 53 -x 192.168.43.1 @192.168.43.1

dig AXFR -p 53 @192.168.43.1

nmap -vv --reason -Pn -T4 -sV -p 53 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/tcp53/tcp_53_dns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/tcp53/xml/tcp_53_dns_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_quick_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_quick_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_quick_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml" 192.168.43.1

dig -p 53 -x 192.168.43.1 @192.168.43.1

dig AXFR -p 53 @192.168.43.1

nmap -vv --reason -Pn -T4 -sV -p 53 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/tcp53/tcp_53_dns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/tcp53/xml/tcp_53_dns_nmap.xml" 192.168.43.1

dig -p 53 -x 192.168.43.1 @192.168.43.1

dig AXFR -p 53 @192.168.43.1

nmap -vv --reason -Pn -T4 -sU -sV -p 53 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/udp53/udp_53_dns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/udp53/xml/udp_53_dns_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -sV -p 5353 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/udp5353/udp_5353_multicastdns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/udp5353/xml/udp_5353_multicastdns_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_quick_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_quick_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml" 192.168.43.1

dig -p 53 -x 192.168.43.1 @192.168.43.1

dig AXFR -p 53 @192.168.43.1

nmap -vv --reason -Pn -T4 -sV -p 53 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/tcp53/tcp_53_dns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/tcp53/xml/tcp_53_dns_nmap.xml" 192.168.43.1

dig -p 53 -x 192.168.43.1 @192.168.43.1

dig AXFR -p 53 @192.168.43.1

nmap -vv --reason -Pn -T4 -sV -p 53 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/tcp53/tcp_53_dns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/tcp53/xml/tcp_53_dns_nmap.xml" 192.168.43.1

dig -p 53 -x 192.168.43.1 @192.168.43.1

dig AXFR -p 53 @192.168.43.1

nmap -vv --reason -Pn -T4 -sU -sV -p 53 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/udp53/udp_53_dns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/udp53/xml/udp_53_dns_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -sV -p 5353 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/udp5353/udp_5353_multicastdns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/udp5353/xml/udp_5353_multicastdns_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_quick_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_quick_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml" 192.168.43.1

dig -p 53 -x 192.168.43.1 @192.168.43.1

dig AXFR -p 53 @192.168.43.1

nmap -vv --reason -Pn -T4 -sV -p 53 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/tcp53/tcp_53_dns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/tcp53/xml/tcp_53_dns_nmap.xml" 192.168.43.1

dig -p 53 -x 192.168.43.1 @192.168.43.1

dig AXFR -p 53 @192.168.43.1

nmap -vv --reason -Pn -T4 -sU -sV -p 53 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/udp53/udp_53_dns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/udp53/xml/udp_53_dns_nmap.xml" 192.168.43.1

nmap -vv --reason -Pn -T4 -sU -sV -p 5353 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/udp5353/udp_5353_multicastdns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/udp5353/xml/udp_5353_multicastdns_nmap.xml" 192.168.43.1


```