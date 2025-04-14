# volt-typhoon-OSINT-project-report
OSINT investigation and threat actor profiling of Volt Typhoon using tools like VirusTotal, Shodan, and Maltego.

This repository contains an open-source intelligence (OSINT) investigation of the threat actor Volt Typhoon, known for targeting U.S. critical infrastructure. The project includes threat actor profiling, infrastructure mapping, and IOC documentation based on publicly available indicators and reconnaissance using tools like:

- Shodan
- VirusTotal
- Maltego (graph coming soon)
- HaveIBeenPwned
- MITRE ATT&CK

## 📁 Project Contents
- `maltego-graph.png` – Visual mapping of known C2 infrastructure
- `IOCs.md` – List of IPs, domains, and other indicators
- `README.md` – Overview and context
- `screenshots/` – OSINT findings and tool outputs
- 
## 📸 Highlights![github project CTI 1](https://github.com/user-attachments/assets/dbf1ec9b-cf67-4e31-8e6e-654d9ff44ad5)

> Screenshots available in the `/screenshots` folder with captions that explain:

- VirusTotal results confirming domain reputations
![github project CTI 2](https://github.com/user-attachments/assets/445ae427-ef57-41e1-85ad-edc2934deb9a)
![github project CTI 4](https://github.com/user-attachments/assets/7b1f59d5-b6bb-4645-b1f7-992583891f1b)
![github project CTI 5](https://github.com/user-attachments/assets/01c818cf-c312-4e68-b312-e3245ec87bfe)
![github project CTI 6](https://github.com/user-attachments/assets/d98f01e9-a3c9-429d-8b5a-a10f9bc29c61)
![github project CTI 7](https://github.com/user-attachments/assets/7f05877e-5896-43dc-9993-e08409af9b0b)
![github project CTI 8](https://github.com/user-attachments/assets/f1d621ce-fe2e-458a-b8c0-7f307e32a386)
![github project CTI 9](https://github.com/user-attachments/assets/e33eb7fd-3c27-44bd-9b3e-af43ca30396e)

- Shodan scans showing exposed services
- Maltego graph (to be added) showing connections across assets
- Breach check hits from HaveIBeenPwned

## 🧩 Tools & Techniques
- **Shodan** – IP/domain reconnaissance, service discovery
- **VirusTotal** – Domain/IP reputation and passive DNS
- **Maltego CE** – Infrastructure relationship mapping
- **HaveIBeenPwned** – Credential exposure check
- **Recon-ng** – Passive reconnaissance and enrichment

- **MITRE ATT&CK** – Mapping adversary TTPs
![TTP Mapping Screenshot](https://github.com/user-attachments/assets/b1a6d01b-4a95-4339-ba84-06b2bc77d983)

## ✅ Key Takeaways
- Volt Typhoon’s infrastructure demonstrates stealthy, living-off-the-land tactics
- Multiple domains linked via passive DNS and shared hosting metadata
- MITRE ATT&CK techniques observed include [T1071.001 – Web Protocols], [T1083 – File and Directory Discovery]

## 📌 Disclaimer
This project is for educational and portfolio purposes only.
