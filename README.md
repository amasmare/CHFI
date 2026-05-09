# مختبرات التحليل الجنائي الرقمي
## CHFI — Digital Forensics Interactive Labs

> Designed by **Eng. Abdullah Alasmari**  
> Based on: *التحليل الجنائي الرقمي* — Dr. Jamil Hussein Tawileh

---

## 📖 About

A fully interactive, browser-based training lab suite built to complement the Arabic digital forensics textbook **"التحليل الجنائي الرقمي"** by Dr. Jamil Hussein Tawileh. All 11 chapters of the book are covered across 7 interactive labs.

Students can access the labs directly from any device — no installation, no internet required after loading, and no backend server needed. Everything runs in the browser.

🔗 **Live Site:** [https://amasmare.github.io/CHFI/](https://amasmare.github.io/CHFI/)

---

## 🧪 Labs Overview

| # | Lab | Topics Covered | Book Chapter(s) | Points |
|---|-----|---------------|-----------------|--------|
| 1 | [أساسيات التحليل الجنائي](lab.html) | Evidence Collection · dd Imaging · Hash Verification · FAT32/NTFS Recovery · Registry · Wireshark · Formal Report | 1, 3, 4 | 100 |
| 2 | [التشفير وأمن المعلومات](crypto-lab.html) | MD5 · SHA · Avalanche Effect · Caesar · XOR · RSA · Rainbow Tables · Salt · LSB Steganography · Password Strength | 2 | — |
| 3 | [جنائيات الويب والبريد](web-forensics.html) | SQL Injection · XSS · Session Hijacking · Email Header Analysis · SPF/DKIM/DMARC · Apache Web Logs | 5 | 75 |
| 4 | [الجنائيات المحمولة](mobile-forensics.html) | SIM/IMSI/ICCID · IMEI/Luhn · Android SQLite · iOS Backup · EXIF GPS · Cell Tower Tracking | 6 | 90 |
| 5 | [تحليل البرمجيات الخبيثة](malware-lab.html) | Malware Types · Static Analysis · PE Header · Dynamic Analysis · Cuckoo Sandbox · IOC · YARA Rules | 7 | 75 |
| 6 | [RAM والأقراص وLinux](ram-disk-lab.html) | Volatile RAM · Volatility Framework · MBR/GPT · NTFS/MFT · Linux /var/log · ext4/Inode | 8, 9 | 90 |
| 7 | [مضادات الجنائيات والجداول الزمنية](anti-forensics-lab.html) | Timestomping · $SI vs $FN · File Wiping · Office Metadata · EXIF/PRNU · Incident Timeline | 10, 11 | 60 |

**Total: 490 points across all quizzes**

---

## ✨ Features

- **100% browser-based** — no server, no database, no installation
- **Offline capable** — download and open locally without internet
- **iOS & Android compatible** — tested on iPhone, iPad, and Android devices
- **Progress tracking** — localStorage saves quiz scores per lab; index shows progress bars
- **Arabic RTL** — fully right-to-left layout with Arabic content
- **Interactive simulations** — real MD5 computation, SQL injection demos, Volatility output, YARA rules, and more
- **Consistent case narrative** — "خالد" (Khalid) is the suspect across all labs for a coherent investigation story

---

## 📚 Book Coverage

All 11 chapters of **التحليل الجنائي الرقمي** are covered:

| Chapter | Topic | Lab |
|---------|-------|-----|
| 1 | مقدمة في الجنائيات الرقمية | Lab 1 |
| 2 | التشفير وأمن المعلومات | Lab 2 |
| 3 | نظم الملفات واسترداد البيانات | Lab 1 |
| 4 | الشبكات وتحليل الحزم | Lab 1 |
| 5 | الجرائم الإلكترونية والويب | Lab 3 |
| 6 | الجنائيات المحمولة | Lab 4 |
| 7 | البرمجيات الخبيثة | Lab 5 |
| 8 | جنائيات الذاكرة والأقراص | Lab 6 |
| 9 | Linux وأنظمة الملفات | Lab 6 |
| 10 | مضادات التحليل الجنائي | Lab 7 |
| 11 | التحقيق وإعداد التقارير | Lab 1 + Lab 7 |

---

## 🚀 Usage

### Online
Open the live site: **[https://amasmare.github.io/CHFI/](https://amasmare.github.io/CHFI/)**

### Offline
1. Download or clone this repository
2. Open `index.html` in any modern browser
3. Navigate to any lab — no setup needed

```bash
git clone https://github.com/amasmare/CHFI.git
cd CHFI
# Open index.html in your browser
```

### Compatibility
| Platform | Browser | Status |
|----------|---------|--------|
| Windows | Chrome, Edge, Firefox | ✅ Full support |
| macOS | Safari, Chrome | ✅ Full support |
| iPhone / iPad | Safari | ✅ Full support |
| Android | Chrome | ✅ Full support |

---

## 🗂 File Structure

```
CHFI/
├── index.html              # Main dashboard — links all labs
├── lab.html                # Lab 1: Forensics fundamentals
├── crypto-lab.html         # Lab 2: Cryptography & security
├── web-forensics.html      # Lab 3: Web & email forensics
├── mobile-forensics.html   # Lab 4: Mobile forensics
├── malware-lab.html        # Lab 5: Malware analysis
├── ram-disk-lab.html       # Lab 6: RAM, disk & Linux forensics
└── anti-forensics-lab.html # Lab 7: Anti-forensics & timelines
```

---

## ⚠️ Disclaimer

All simulations, attack demonstrations, and forensic scenarios in these labs are **strictly for educational purposes**. No real systems are targeted. All data, IP addresses, and case details are fictional and created solely for training.

---

## 👨‍💻 Author

**Eng. Abdullah Alasmari — م. عبدالله الأسمري**

Based on: **التحليل الجنائي الرقمي** — Dr. Jamil Hussein Tawileh

© 2025 · All content for academic and educational use only
