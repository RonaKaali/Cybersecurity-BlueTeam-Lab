# 🛡️ Alexander's Cybersecurity Journey: Blue Team & Automation Lab

Selamat datang di repositori dokumentasi belajar saya. Di sini saya merangkum transisi saya dari memahami taktik penyerangan (Red Team) hingga membangun sistem pertahanan proaktif (Blue Team).

## 🧪 Custom Tools & Automation
Sebagai bagian dari efisiensi kerja, saya mengembangkan script otomatisasi sederhana:

* **AlexLab:** Bash script untuk mengotomatisasi penyiapan lingkungan (Environment) audit, perbaikan DNS, dan aktivasi keamanan dasar (Firewall).
* **AlexScan:** Wrapper script berbasis Nmap untuk melakukan reconnaissance secara terstruktur dan menghasilkan laporan otomatis.

---

## 📑 Project Modules

### 1. Offensive Security Awareness (Red Team)
Memahami celah keamanan dari sudut pandang penyerang untuk membangun pertahanan yang lebih baik.
* **Network Recon:** Menggunakan `Nmap` (AlexScan) untuk pemetaan port dan identifikasi service.
* **Packet Sniffing:** Analisis trafik data menggunakan `Wireshark` untuk mengidentifikasi protokol yang tidak aman.
* **Social Engineering:** Simulasi Credential Harvesting untuk memahami vektor serangan phishing.

### 2. Defensive Hardening (Blue Team)
Proses memperkuat sistem (Hardening) dan audit berkala.
* **System Auditing:** Menggunakan `Lynis` untuk penilaian keamanan sistem Linux (Hardening Index: 65).
* **Firewall Management:** Implementasi `UFW` (Uncomplicated Firewall) dengan kebijakan *Strict Inbound*.
* **Endpoint Security:** Penggunaan `Auditd` untuk melacak aktivitas sistem yang mencurigakan.

### 3. Monitoring & Incident Response
Mendeteksi dan merespon ancaman secara real-time.
* **Log Analysis:** Pemantauan log sistem melalui `journalctl` dan `syslog`.
* **Brute Force Detection:** Identifikasi manual kegagalan otentikasi (Auth Failure) melalui analisis pola log.
* **Integritas Data:** Implementasi File Integrity Monitoring (FIM) manual menggunakan hashing SHA256 pada file sensitif `/etc/passwd`.

---

## 🛠️ Tech Stack & Lab Environment
* **OS:** Kali Linux (VMware/VirtualBox)
* **Tools:** Nmap, Wireshark, Lynis, UFW, Docker, Bash Scripting.
* **Hardware:** Lenovo IdeaPad 3 (8GB RAM).

---

## 📈 Next Steps
* [ ] Implementasi SIEM menggunakan Wazuh.
* [ ] Memperdalam Digital Forensics (Autopsy/Volatility).
* [ ] Persiapan sertifikasi CompTIA Security+.

---
*“Security is not a product, but a process.”*


![Detection Screenshot](screenshots/detect-bruteforce.png)

