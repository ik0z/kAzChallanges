### kAz Cyber challenge#1

Useful tools :

1- ffuf,gobuster

```
gobuster dir -u http://target.com/ -w /usr/share/seclists/Discovery/Web-Content/directory-list-2.3-small.txt --random-agent

ffuf -w /usr/share/seclists/Discovery/Web-Content/directory-list-2.3-small.txt.txt:FUZZ -u http://FUZZ.target.com -ic

```


2- Netcat , Metasploit : 
```
nc -nvlp 4444

msfconsole -q
msf> use multi/handler
msf> set lport 4444
msf> set lhost 10.0.x.x
```

3- RCE Reverse shell :
https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet


#### keep going on
