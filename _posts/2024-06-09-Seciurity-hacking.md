---
layout: post
---

## Wyszukiwarki
* <https://www.startpage.com/pl/> - oparta na silniuku Google
* <https://www.qwant.com/> - Francuska oparta na Bingu k
* <https://duckduckgo.com> 

## Różne
* <https://www.sejda.com/> - edytor PDF 


```bash
# Pełne skanowanie Nmapa, uruchamia ukrywanie synchronizacji, czas T4
nmap -v -sS -A -T4 cel
# Jak wyżej, ale skanuje wszystkie porty TCP (trwa znacznie dłużej)
nmap -v -sS -p–A -T4 cel
# Jak wyżej, ale skanuje wszystkie porty TCP i skanowanie UDP (trwa jeszcze dłużej)
nmap -v -sU -sS -p- -A -T4 cel
# Skrypt Nmap do skanowania w poszukiwaniu podatnych na ataki serwerów SMB
nmap -v -p 445 –script=smb-check-vulns –script -args=unsafe=1 192.168.1.X
# Wyświetla wszystkie porty, które są aktualnie używane 
nmap localhost
# Wyszukaj w skryptach nmap słowa kluczowe
ls /usr/share/nmap/scripts/* | grep ftp    
```

## Hacking
* <https://book.hacktricks.xyz> -
* <https://old.reddit.com/r/hacking/wiki/index>
* <https://www.hackingarticles.in/>
* <https://www.programiz.com/>
