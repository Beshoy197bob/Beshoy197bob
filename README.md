<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0D1117,50:00FF9C,100:FF0055&height=240&section=header&text=besh0x79&fontSize=70&fontColor=ffffff&fontAlignY=38&desc=//%20cloud%20%26%20network%20pentester%20%7C%20pwn%20addict&descAlignY=60&descSize=18&animation=twinkling" width="100%" alt="header" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2800&pause=900&color=00FF9C&center=true&vCenter=true&width=760&height=50&lines=%24+whoami+%E2%86%92+besh0x79;%5B%2B%5D+Aspiring+Cloud+%26+Network+Pentester;%5B%2B%5D+AWS+Security+%7C+Binary+Exploitation+%7C+CTF;%5B%2A%5D+Break+it+legally.+Learn+it+deeply.+Share+it+openly." alt="Typing SVG" />

<br/>

![Status](https://img.shields.io/badge/STATUS-HUNTING_BUGS-00FF9C?style=flat-square&labelColor=0D1117)
![Mode](https://img.shields.io/badge/MODE-PWN_%2F_CLOUD-FF0055?style=flat-square&labelColor=0D1117)
![Ethics](https://img.shields.io/badge/ETHICS-WHITE_HAT-00B8FF?style=flat-square&labelColor=0D1117)
![Flags](https://img.shields.io/badge/FLAGS-CAPTURING-FFD400?style=flat-square&labelColor=0D1117)

</div>

---

## `[ 0x00 ]` About Me

```bash
root@besh0x79:~# cat about_me.txt

[☁️]  Breaking into AWS and networks (legally): IAM abuse, S3 misconfigs, lateral movement
[🚩]  Looking to team up for CTFs and cloud security research
[🎯]  Next target: AWS privilege escalation, network pivoting, and heap exploitation
[📚]  Learning: AWS pentesting, network pentesting, and binary exploitation
[💬]  Ask me about: AWS security, network pentesting, CTFs, and pentest methodology
[⚡]  Behind every vulnerability is a human assumption that turned out to be wrong
```

---

## `[ 0x01 ]` Pwn Terminal

```bash
root@besh0x79:~/pwn# checksec --file=./vuln

    Arch:     amd64-64-little
    RELRO:    Partial RELRO
    Stack:    No canary found      ← 👀 interesting
    NX:       NX enabled
    PIE:      No PIE (0x400000)    ← 👀 very interesting

root@besh0x79:~/pwn# python3 exploit.py
[+] Starting local process './vuln': pid 1337
[*] Leaking libc via puts@GOT ...
[+] libc base  : 0x7f3a1c200000
[*] Building ROP chain: pop rdi ; ret → /bin/sh → system
[*] Switching to interactive mode
$ id
uid=0(root) gid=0(root) groups=0(root)
$ cat flag.txt
flag{h0man_n4tur3_h4s_n0_p4tch}
```

---

## `[ 0x02 ]` Current Focus

<div align="center">

| 🎯 Domain | ⚔️ Attack Surface | 📈 Progress |
|:---|:---|:---|
| ☁️ **Cloud (AWS)** | IAM misconfigs · S3 exposure · privesc paths | ![](https://img.geekyz.me/progress-bar/70) |
| 🌐 **Network** | Recon · pivoting · lateral movement · post-exploitation | ![](https://img.geekyz.me/progress-bar/60) |
| 🧬 **Binary Exploitation** | Stack overflow · ROP · format strings → heap | ![](https://img.geekyz.me/progress-bar/45) |

</div>

---

## `[ 0x03 ]` Attack Roadmap

```text
 RECON ───► ENUM ───► EXPLOIT ───► PRIVESC ───► PIVOT ───► LOOT
   │          │          │            │            │         │
  nmap     IAM/S3     ROP/fmt      sudo/SUID    chisel    flag{}
```

---

## `[ 0x04 ]` Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,py,bash,powershell,aws,azure,linux&theme=dark&perline=8" alt="tech stack" />

</div>

---

## `[ 0x05 ]` Security Arsenal

<div align="center">

<img src="https://skillicons.dev/icons?i=kali,linux&theme=dark" alt="os" />

<br/><br/>

![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat-square&logo=nmap&logoColor=white&labelColor=0D1117)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white&labelColor=0D1117)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white&labelColor=0D1117)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white&labelColor=0D1117)
![GDB](https://img.shields.io/badge/GDB_+_pwndbg-FF0055?style=flat-square&logo=gnu&logoColor=white&labelColor=0D1117)
![pwntools](https://img.shields.io/badge/pwntools-00FF9C?style=flat-square&logo=python&logoColor=0D1117&labelColor=0D1117)
![OWASP](https://img.shields.io/badge/OWASP-00B8FF?style=flat-square&logo=owasp&logoColor=white&labelColor=0D1117)

</div>

---

## `[ 0x06 ]` CTF & Labs

<div align="center">

[![Hack The Box](https://img.shields.io/badge/Hack_The_Box-9FEF00?style=flat-square&logo=hackthebox&logoColor=111927&labelColor=111927)](https://app.hackthebox.com/users/2457343)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-C11111?style=flat-square&logo=tryhackme&logoColor=white&labelColor=212C42)](https://tryhackme.com/p/Besh0x79)
[![CyLab](https://img.shields.io/badge/CyLab_/_picoCTF-B66BFF?style=flat-square&logoColor=white&labelColor=1a1025)](https://learn.cylabacademy.org/users/Beshoy)

</div>

---

## `[ 0x07 ]` GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.shion.dev/api?username=besh0x79&hide_border=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=00FF9C&text_color=C9D1D9&icon_color=FF0055&ring_color=00FF9C" alt="Stats" />
<img height="170" src="https://github-readme-stats.shion.dev/api/top-langs/?username=besh0x79&hide_border=true&layout=compact&bg_color=0D1117&title_color=00FF9C&text_color=C9D1D9" alt="Top Langs" />

<br/>

<img src="https://streak-stats.demolab.com/?user=besh0x79&hide_border=true&background=0D1117&ring=00FF9C&fire=FF0055&currStreakNum=00FF9C&currStreakLabel=00FF9C&sideNums=C9D1D9&sideLabels=8B949E&dates=8B949E" alt="Streak" />

</div>

---

## `[ 0x08 ]` Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0D1117)](https://linkedin.com/in/besh0x79)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white&labelColor=0D1117)](https://youtube.com/@besh0x79)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white&labelColor=0D1117)](mailto:black.root.zero@gmail.com)

<br/>

```bash
root@besh0x79:~# echo "Human nature has no patch.."
Human nature has no patch..
root@besh0x79:~# exit
```

![Profile Views](https://komarev.com/ghpvc/?username=besh0x79&color=00ff9c&style=flat-square&label=Profile+views)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF0055,50:00FF9C,100:0D1117&height=110&section=footer" width="100%" alt="footer" />

</div>
