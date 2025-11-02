<div align="center">

# CTF Write-ups 🏴‍☠️  
**مستندسازی چالش‌های TryHackMe, HackTheBox, PicoCTF**  
**by YourName | White Hat Hacker**

[![CTF](https://img.shields.io/badge/CTF-Player-blue)](#)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top_5%25-success)](#)
[![Stars](https://img.shields.io/github/stars/yourname/ctf-writeups?style=social)](#)

![TryHackMe Banner](screenshots/tryhackme_banner.jpg)

</div>

---

## 📊 چالش‌های حل شده

| پلتفرم | ماشین | سطح | تاریخ | لینک |
|--------|-------|-----|-------|------|
| TryHackMe | Blue | Easy | 2025-03-15 | [Write-up](TryHackMe/Blue/writeup.md) |
| TryHackMe | Mr. Robot | Medium | 2025-04-01 | [Write-up](TryHackMe/MrRobot/writeup.md) |
| HackTheBox | Lame | Easy | 2025-04-10 | [Write-up](HackTheBox/Lame/writeup.md) |

> **هدف:** حداقل **۱ چالش در هفته** → **۵۰ تا تا آخر سال**

---

## 📸 پیش‌نمایش چالش "Blue"

![CTF Overview](screenshots/ctf_overview.png)

---

## ساختار هر Write-up

```markdown
# TryHackMe - Blue

**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/blue  
**Date:** 2025-03-15  
**Flag:** `THM{...}`

---

## 1. Nmap Scan
```bash
nmap -sV -p- 10.10.10.40
