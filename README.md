<h1 align="center">🛡️ GPTScanner</h1>
<p align="center">
  <strong>Advanced Vulnerability Scanner powered by OPEN-AI</strong><br>
  Lightweight | Modular | Updated 2025 | SQLi, XSS, LFI & more
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-active-success?style=flat-square" />
  <img src="https://img.shields.io/github/license/tuonome/GPTScanner?style=flat-square" />
  <img src="https://img.shields.io/github/stars/tuonome/GPTScanner?style=social" />
</p>

---

## 🚀 Panoramica

**GPTScanner** è uno strumento avanzato di *web vulnerability scanning* potenziato da logica automatizzata e moduli personalizzabili.  
Supporta l'individuazione di vulnerabilità comuni come **SQL Injection**, **XSS**, **LFI**, e include un **crawler intelligente**, **dumper database**, supporto per **payload personalizzati**, ed esportazione CSV.

---

## 🧰 Caratteristiche

- [x] Crawler intelligente e profondo (fino a 5 livelli)
- [x] Rilevamento SQLi, XSS, LFI aggiornato al 2025
- [x] Dump automatico database (opzionale)
- [x] Interfaccia web con evidenziazione vulnerabilità
- [x] Supporto per payload personalizzati
- [x] Esportazione risultati in CSV
- [x] Modalità headless + opzione `-h` per help avanzato

---

## 📸 Screenshot

<p align="center">
  <img src="images/interface.png" width="700" alt="Interfaccia principale">
  <br>
  <em>Interfaccia di scansione con evidenziazione vulnerabilità in tempo reale</em>
</p>

---

## ⚙️ Installazione

```bash
git clone https://github.com/tuonome/GPTScanner.git
cd GPTScanner
pip install -r requirements.txt
python gptscanner.py -u https://target.com -o results.csv
