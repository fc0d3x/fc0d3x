```text
$ ./operator --id fc0d3x --verbose

> operator:          fc0d3x
> status:            ACTIVE
> specialization:    OFFENSIVE SECURITY
> objective:         THINK. BREAK. LEARN. REPEAT.


$ whoami

fc0d3x


$ ls -la

drwxr-xr-x  skills/               # offensive + defensive skills
drwxr-xr-x  labs/                 # practical training
drwxr-xr-x  training/             # courses + certifications
-rw-r--r--  operator.profile      # identity + focus
-rw-r--r--  web_targets.scope     # web security focus
-rw-r--r--  network_targets.scope # network + AD focus
-rwxr-xr-x  toolchain             # tools + platforms
-rw-r--r--  language.pack         # languages
-rw-------  connect.secure        # contact channels


$ cat operator.profile

Cybersecurity enthusiast focused on offensive security,
web exploitation, Active Directory, reconnaissance,
privilege escalation, and defensive workflows.


$ tree skills/

skills/
|-- offensive/
|   |-- reconnaissance
|   |-- enumeration
|   |-- web_testing
|   |-- exploitation
|   |-- privilege_escalation
|   |-- active_directory
|   `-- post_exploitation
|
`-- defensive/
    |-- log_analysis
    |-- alert_triage
    |-- siem_fundamentals
    |-- network_defense
    |-- hardening
    `-- threat_detection


$ cat web_targets.scope

[+] XSS
[+] SQL Injection
[+] Command Injection
[+] CSRF
[+] IDOR
[+] Authentication flaws
[+] Access-control weaknesses


$ cat network_targets.scope

[+] Service enumeration
[+] SMB / LDAP workflows
[+] Active Directory attack paths
[+] Local privilege escalation
[+] Misconfiguration discovery
[+] Lateral movement concepts


$ ./toolchain --list

[recon]
  Shodan
  Nmap
  Masscan
  Gobuster
  Recon-ng
  Aircrack-ng

[web]
  Burp Suite
  SQLmap
  Wfuzz

[network]
  Wireshark
  Netcat
  smbclient
  ldapsearch

[active_directory]
  BloodHound
  SharpHound
  Mimikatz

[password_attacks]
  Hydra
  John the Ripper

[exploitation]
  Metasploit
  BeEF

[vulnerability_scanning]
  Nessus
  OpenVAS

[scripting]
  Python
  Bash
  PowerShell

[platforms]
  Kali Linux
  Ubuntu
  Debian
  Windows
  Windows Server
  macOS


$ ls labs/

TryHackMe/
PortSwigger_Web_Security_Academy/
Hack_The_Box/
Home_lab/

$ cat labs/summary.log

[+] 100+ practical labs and exercises
[+] offensive + defensive security practice
[+] web + network + Active Directory scenarios
[+] methodology + documentation focused

highlights:
  - Industrial Intrusion
  - Hackfinity Battle
  - Hacker Holidays 2026

$ ls training/

Cyber_Security_and_Ethical_Hacking
IBM_Ethical_Hacking_with_Open_Source_Tools
PortSwigger_Web_Security_Academy
TryHackMe_Practical_Labs
Hack_The_Box_Practice
Home_lab

$ cat language.pack

Bulgarian   : fluent
Macedonian  : fluent
English     : fluent
Serbian     : conversational


$ cat connect.secure

GitHub    : https://github.com/fc0d3x
TryHackMe : https://tryhackme.com/p/fc0d3x
X         : https://x.com/fc0d3x21448
Email     : filipjovanovv@proton.me


$ echo "THINK. BREAK. LEARN. REPEAT."

THINK. BREAK. LEARN. REPEAT.
