# Ultimate_Osint

**Ultimate_Osint** is a powerful and modular OSINT (Open Source Intelligence) toolkit designed specifically for Linux. It provides cybersecurity professionals, penetration testers, and investigators with a wide array of tools to collect, analyze, and correlate open-source information from various platforms.

---

## 🧰 Features

- Modular design with easy-to-use CLI
- Integrates multiple popular OSINT tools in one place
- Information gathering from social media, email, phone, IPs, domains, usernames, and more
- Lightweight and customizable for Linux systems
- Automated report generation

---

## 🔍 Tools Included

### 🧑 User Recon
- **Sherlock** – Search usernames across social networks
- **Maigret** – Collect a dossier on a person by username
- **WhatsMyName** – Perform username checks on hundreds of platforms

### 📧 Email Investigation
- **EmailRep** – Reputation check on email addresses
- **Holehe** – Check if email is used on online services
- **Hunter.io API** – Find email patterns for domains

### 🌐 Domain & IP Investigation
- **theHarvester** – Collect emails, subdomains, and hosts
- **DNSdumpster** – DNS recon and mapping
- **Shodan** – Find devices and ports on the internet
- **whois / dig / nslookup** – Built-in Linux DNS tools

### 📱 Phone Number Intelligence
- **Numverify API** – Lookup phone details
- **PhoneInfoga** – Scan international phone numbers

### 🖼️ Image & Metadata
- **ExifTool** – Extract metadata from images and documents
- **Tineye / Google Reverse Image Search** – Image origin lookup

### 🐦 Social Media OSINT
- **Twint** – Twitter scraping (no login/API required)
- **Instaloader** – Download public Instagram posts & metadata
- **Facebook Graph Search (via web tools)** – People and page search

### 📍 Geolocation Tools
- **Creepy** – Geolocation data from social media
- **Google Earth + OpenStreetMap APIs** – Visual location analysis

### 🛠️ Other Utilities
- **Wayback Machine Scraper** – Archive lookups
- **Metagoofil** – Metadata from public documents
- **Pipl / Spokeo / PeopleFinders** – (via browser or APIs)
- **BreachCheck** – Check if emails/usernames were in data breaches

---

## 🐧 Installation

### Prerequisites

- Linux (Ubuntu/Debian-based recommended)
- Python 3.8+
- Git
- curl / wget

### Clone the repository:

```bash
git clone https://github.com/SetoPahadGames/Ultimate_Osint.git
cd Ultimate_Osint
