<div align="center">

# DOIT Earthquake Early Warning Product Portfolio

### MA301+ · EQ-Alarmer · Earthquake Early Warning · Structural Health Monitoring

[![Website](https://img.shields.io/badge/Live%20Portfolio-GitHub%20Pages-1f6feb?style=for-the-badge&logo=github)](https://antvir.github.io/DOIT-product_portfolio/)
[![Company](https://img.shields.io/badge/Company-DOIT%20Co.%2C%20Ltd.-0A84FF?style=for-the-badge)](https://www.k-doit.com)
[![Status](https://img.shields.io/badge/Status-Active-00C853?style=for-the-badge)](https://antvir.github.io/DOIT-product_portfolio/)

**Interactive multilingual product portfolio for DOIT earthquake early warning and seismic monitoring solutions.**

</div>

---

## Overview

This repository contains the interactive web portfolio for **DOIT Co., Ltd.** earthquake early warning and seismic monitoring products.

The portfolio presents the complete earthquake-response workflow through an interactive building scenario, product information, software capabilities, and deployment references.

### Main products

- **MA301+** seismic accelerometer
- **EQ-Alarmer** earthquake alarm and monitoring device
- Earthquake Early Warning (EEW)
- Real-time seismic monitoring
- Structural Health Monitoring (SHM)
- Monitoring and integration software

---

## Live Portfolio

Open the deployed GitHub Pages site:

**https://antvir.github.io/DOIT-product_portfolio/**

---

## Main Features

| Feature | Description |
|---|---|
| **Interactive Building Scenario** | Visual explanation of earthquake detection, warning, strong shaking and post-event monitoring |
| **360° Product Viewer** | Interactive product presentation for DOIT seismic hardware |
| **MA301+ Product Information** | Specifications, triggering functions and seismic measurement features |
| **EQ-Alarmer Information** | Estimated intensity, earthquake warning and monitoring functions |
| **Real-Time Monitoring** | Seismic waveform, event and system-status monitoring presentation |
| **Structural Health Monitoring** | Post-earthquake structural-response assessment workflow |
| **Software Integration** | Earthworm, SeedLink and seismic-data processing/integration information |
| **Deployment References** | Installation and project references based on DOIT product materials |
| **Multilingual Interface** | English, Bangla, Mongolian, Japanese, Filipino and Korean |

---

## Earthquake Early Warning Workflow

The interactive portfolio explains the earthquake-response process in seven stages:

1. MA301+ sensors monitor seismic motion
2. EQ-Alarmer receives and processes measurement information
3. An earthquake occurs
4. P-wave / event detection begins
5. Local warning and configured outputs are activated
6. Users can take protective action
7. Stronger shaking arrives while monitoring continues

The portfolio also introduces the complete lifecycle:

**Before strong shaking → During the earthquake → After strong shaking**

---

## Products

### MA301+

DOIT's MEMS-type seismic accelerometer for seismic measurement, earthquake early warning and structural monitoring applications.

Key functions presented in the portfolio include:

- 3-axis acceleration measurement
- PGA, Pd and STA/LTA trigger algorithms
- NTP / GPS / RTC time synchronization
- Ethernet TCP/IP or UDP communication
- PoE power and communication
- Local event detection and monitoring integration
- IP67 enclosure
- Seismic monitoring software integration

### EQ-Alarmer

Earthquake alarm and monitoring device supporting:

- Estimated seismic intensity information
- Earthquake warning
- Real-time monitoring
- Existing seismometer integration
- Voice and LED alarm output
- Contact / relay output
- Software monitoring
- Optional structural health monitoring configuration

---

## Software & Integration

The portfolio presents DOIT monitoring and integration functions including:

- Real-time seismic measurement monitoring
- Waveform monitoring
- Event information monitoring
- Event reports
- Data storage, transmission and analysis
- Observation-site reception and system status
- Earthworm integration
- SeedLink integration
- Raw and MMA data processing
- QSCD20 data collection and storage

---

## Languages

The portfolio supports:

- English
- Bangla
- Mongolian
- Japanese
- Filipino
- Korean

The language selector changes the supported interface and portfolio text while keeping technical product names unchanged.

---

## Repository Structure

```text
DOIT-product_portfolio/
│
├── index.html
├── README.md
└── .git/
```

The portfolio is designed as a self-contained HTML presentation.

---

## Running Locally

No build process is required.

```bash
git clone https://github.com/antvir/DOIT-product_portfolio.git
cd DOIT-product_portfolio
```

Then open `index.html` in a modern web browser.

---

## Updating the Portfolio

Most portfolio content is maintained directly inside `index.html`.

For wording changes:

1. Search for the exact English sentence in `index.html`.
2. Edit the visible HTML text.
3. If the sentence is multilingual, update the matching entry inside:

```javascript
window.DOIT_TRANSLATIONS
```

Avoid changing the Three.js / WebGL / canvas rendering code unless the visual workflow itself needs to be modified.

---

## Deployment

This repository is deployed using **GitHub Pages**.

After editing:

```bash
git add index.html README.md
git commit -m "Update DOIT portfolio"
git push origin main
```

Live site:

**https://antvir.github.io/DOIT-product_portfolio/**

---

## About DOIT Co., Ltd.

**DOIT Co., Ltd.** develops earthquake monitoring, earthquake early warning, structural monitoring and industrial monitoring solutions.

Website: **https://www.k-doit.com**

Address:  
10-40, Hakhajungang-ro 127beon-gil, Yuseong-gu, Daejeon, Republic of Korea

---

## License

This portfolio and its associated product materials are proprietary content of **DOIT Co., Ltd.**

© 2026 DOIT Co., Ltd. All rights reserved.
