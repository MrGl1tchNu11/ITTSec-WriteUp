# 🐺 ITTSecCTF Writeups - Mr.Gl1tchNu11's Digital Archives

<div align="center">

```
"The network is vast and infinite... just like the challenges in this CTF."
                                        - Silver Wolf
```

![Silver Wolf Banner](https://img.shields.io/badge/Player-Mr.Gl1tchNull-silver?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDJMMTMuMDkgOC4yNkwyMCA5TDEzLjA5IDE1Ljc0TDEyIDIyTDEwLjkxIDE1Ljc0TDQgOUwxMC45MSA4LjI2TDEyIDJaIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIi8+Cjwvc3ZnPgo=)
![CTF](https://img.shields.io/badge/CTF-ITTSec%20CTF-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

</div>

## 🎯 About This Repository

Welcome to MrGl1tchNu11's digital archives! This repository contains **complete writeups** for the **ITTSec Capture The Flag** competition, solved with Silver Wolf's signature hacking style from Honkai Star Rail.

Just like Silver Wolf who excels at infiltrating digital systems and cracking complex codes, these writeups will guide you through an epic journey in the cybersecurity world with a systematic and elegant approach.

## 🌟 Challenge Categories

### 💎 **Bonus - Tutorial Realm**

- **What Is CTF?** - Basic introduction for beginner Stellaron Hunters
  - Flag: `ITTSec{hello_ctf_world}`

### 🕸️ **Web Exploitation - Digital Network Infiltration**

1. **Hidden Comment** - Discovering hidden traces in source code

   - Technique: Source code analysis
   - Flag: `ITTSec{d0nt_m155_th3_50urc3_C0d3_R3v13w}`

2. **Kill The Boss V1** - Basic parameter tampering

   - Technique: URL parameter manipulation
   - Flag: `ITTSec{p4r4m3t3r_t4mp3r1ng_ftw}`

3. **Kill The Boss V2** - Base64 encoding with POST requests

   - Technique: Base64 decoding & encoding, HTTP manipulation
   - Flag: `ITTSec{p4r4m3t3r_t4mp3r1ng_v14_p0st_b4s364_ftw}`

4. **Kill The Boss V3** - Advanced cryptographic challenge

   - Technique: AES-CBC decryption, HMAC verification, JavaScript reverse engineering
   - Flag: `ITTSec{AES_crypt_4nd_HMAC_v3r1fy_ftw}`

5. **Unsecured Web** - Local File Inclusion exploitation
   - Technique: LFI via PHP filters
   - Flag: `ITTSec{cl4ss1c_Lfi}`

### 🔐 **Cryptography - Code Breaking Mastery**

1. **P[R]ime [S]hould be [A] very long number** - RSA Cryptanalysis
   - Technique: RSA factorization, prime number analysis
   - Flag: `ITTS{br0k3n_RSA}`

### 📱 **Mobile - Digital Device Penetration**

1. **ITTSec Mobile** - Android APK analysis
   - Technique: String extraction, binary analysis
   - Flag: `ITTSec{e4sy_r3ver53_Flag_s0}`

## 🌌 Repository Structure

```
ITTSecCTF/
├── writeups/
│   ├── web-exploitation/
│   │     ├── HiddenComment.md
│   │     ├── KillTheBossV1.md
│   │     ├── KillTheBossV2.md
│   │     ├── KillTheBossV3.md
│   │     └── UnsecuredWeb.md
│   ├── cryptography/
│   │     └── P[R]ime[S]houldbe[A]verylongnumber.md
│   ├── mobile/
│   │     └── ITTSecMobile.md
│   ├── pwn/
│   │     └── MathMaster.md
│   └── bonus/
│   │     └── WhatIsCTF.md
├── images/
│   ├── web-exploitation/
│   │     ├── KillTheBossV1.png
│   │     ├── KillTheBossV1-1.png
│   │     ├── KillTheBossV1-2.png
│   │     ├── KillTheBossV1-3.png
│   │     ├── KillTheBossV1-4.png
│   │     ├── UnsecuredWeb.png
│   │     ├── UnsecuredWeb1.png
│   │     ├── UnsecuredWeb2.png
│   │     ├── UnsecuredWeb3.png
│   │     ├── UnsecuredWeb4.png
│   │     ├── UnsecuredWeb5.png
│   │     ├── UnsecuredWeb6.png
│   │     ├── KillTheBossV2.png
│   │     ├── KillTheBossV2-1.png
│   │     ├── KillTheBossV2-2.png
│   │     ├── KillTheBossV2-3.png
│   │     ├── KillTheBossV2-4.png
│   │     ├── KillTheBossV2-5.png
│   │     ├── HiddenComment.png
│   │     ├── HiddenComment2.png
│   │     ├── HiddenComment3.png
│   │     ├── KillTheBossV3.png
│   │     ├── KillTheBossV3-1.png
│   │     ├── KillTheBossV3-2.png
│   │     ├── KillTheBossV3-3.png
│   │     ├── KillTheBossV3-4.png
│   │     └── KillTheBossV3-5.png
│   ├── cryptography/
│   │     └── RSA.png
│   ├── pwn/
│   │     ├── MathMaster.png
│   │     ├── MathMaster1.png
│   │     ├── MathMaster2.png
│   │     ├── MathMaster3.png
│   │     ├── MathMaster4.png
│   │     └── MathMaster5.png
│   ├── mobile/
│   │     ├── ITTSecMobile.png
│   │     └── ITTSecMobile1.png
│   └── bonus/
│         └── WhatIsCTF.png
├── pdf/
│    └── Mr Gl1tchNu11 – ITTSec Capture The Flag.pdf
└── README.md
```

## 📋 Challenge Overview

| Category | Challenge                                | Difficulty | Technique                   | Status |
| -------- | ---------------------------------------- | ---------- | --------------------------- | ------ |
| Bonus    | What Is CTF?                             | ⭐         | Reading Comprehension       | ✅     |
| Web      | Hidden Comment                           | ⭐         | Source Code Analysis        | ✅     |
| Web      | Kill The Boss V1                         | ⭐⭐       | Parameter Tampering         | ✅     |
| Web      | Kill The Boss V2                         | ⭐⭐⭐     | Base64 & HTTP Manipulation  | ✅     |
| Web      | Kill The Boss V3                         | ⭐⭐⭐⭐   | AES-CBC & HMAC              | ✅     |
| Web      | Unsecured Web                            | ⭐⭐⭐     | Local File Inclusion        | ✅     |
| Crypto   | P[R]ime [S]hould be [A] very long number | ⭐⭐⭐     | RSA Factorization           | ✅     |
| Mobile   | ITTSec Mobile                            | ⭐⭐       | Android Reverse Engineering | ✅     |

---

<div align="center">

**"Every expert was once a beginner. Every pro was once an amateur."**

_Keep hacking, keep learning! 🐺⚡_

[![Star this repo](https://img.shields.io/github/stars/MrGl1tchNu11/ITTSec-CaptureTheFlag?style=social)](https://github.com/MrGl1tchNu11/ITTSec-CaptureTheFlag)
[![Fork this repo](https://img.shields.io/github/forks/MrGl1tchNu11/ITTSec-CaptureTheFlag?style=social)](https://github.com/MrGl1tchNu11/ITTSec-CaptureTheFlag)

_Made with 💜 by MrGl1tchNu11_

</div>
