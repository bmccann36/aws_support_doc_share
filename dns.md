➜  ~ nslookup api.develop.greensparksoftware.com
Server:		192.168.1.1
Address:	192.168.1.1#53

Non-authoritative answer:
Name:	api.develop.greensparksoftware.com
Address: 3.12.228.69
Name:	api.develop.greensparksoftware.com
Address: 3.13.7.77


➜  ~ dig ns api.develop.greensparksoftware.com

; <<>> DiG 9.10.6 <<>> ns api.develop.greensparksoftware.com
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NOERROR, id: 28483
;; flags: qr rd ra; QUERY: 1, ANSWER: 4, AUTHORITY: 0, ADDITIONAL: 5

;; OPT PSEUDOSECTION:
; EDNS: version: 0, flags:; udp: 1232
;; QUESTION SECTION:
;api.develop.greensparksoftware.com. IN	NS

;; ANSWER SECTION:
api.develop.greensparksoftware.com. 172800 IN NS ns-313.awsdns-39.com.
api.develop.greensparksoftware.com. 172800 IN NS ns-1513.awsdns-61.org.
api.develop.greensparksoftware.com. 172800 IN NS ns-1885.awsdns-43.co.uk.
api.develop.greensparksoftware.com. 172800 IN NS ns-612.awsdns-12.net.

;; ADDITIONAL SECTION:
ns-313.awsdns-39.com.	12939	IN	A	205.251.193.57
ns-612.awsdns-12.net.	11876	IN	A	205.251.194.100
ns-1513.awsdns-61.org.	11801	IN	A	205.251.197.233
ns-1885.awsdns-43.co.uk. 11702	IN	A	205.251.199.93

;; Query time: 45 msec
;; SERVER: 192.168.1.1#53(192.168.1.1)
;; WHEN: Tue Aug 09 16:34:26 EDT 2022
;; MSG SIZE  rcvd: 264

