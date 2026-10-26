<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0f,100:ff4d00&height=190&section=header&text=Sourodyuti%20Biswas%20Sanyal&fontSize=40&fontColor=f6f4ef&fontAlignY=38&desc=Systems%20that%20see%2C%20think%2C%20and%20ship.&descAlignY=58&descColor=f6f4ef" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1000&color=FF4D00&center=true&vCenter=true&width=720&lines=AI+%26+Computer+Vision+Researcher;Technical+Co-founder+%40+CURAA;Co-founder+%40+Curawave+LLP;IEEE+SPACE+2026+author+%C2%B7+COMSYS+H7+champion)](https://www.sourodyuti.me)

[![Portfolio](https://img.shields.io/badge/sourodyuti.me-FF4D00?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.sourodyuti.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sourodyutibs/)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/sourodyutibiswas)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0003-3809-9448)
[![CURAA](https://img.shields.io/badge/CURAA-curaapets.com-141414?style=for-the-badge)](https://curaapets.com)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sourodyuti.biswas.sanyal.14@gmail.com)

</div>

---

## About me

```python
class Sourodyuti:
    roles     = ["AI & computer-vision researcher", "Technical co-founder, CURAA", "Co-founder, Curawave LLP"]
    studying  = "B.Tech CSE @ Techno India University, Kolkata (2024–2028)"
    location  = "Durgapur → Kolkata, India"
    open_to   = ["research", "internships", "collabs"]
    mantra    = "Read the paper Friday, ship the implementation Monday."

    def now(self):
        return [
            "EdgeRF: sub-megabyte RF drone-controller identification (IEEE RadarConf 2027, in preparation)",
            "CURAA: an AI smart collar that listens to what pets can't say (AIC-incubated)",
            "VaaniKavach: on-device detection of AI voice-clone scam calls in Bengali & Hindi",
        ]
```

I build intelligent systems at every scale — TinyML on a pet collar, a Rust trading terminal,
published computer-vision research — and ship all of it myself: firmware, mobile, web, backend and ML.

---

## Highlights

- 📄 **Paper accepted — IEEE SPACE 2026:** *Progressive Knowledge Distillation Framework for Military Vehicle Classification on Edge Devices.* A ResNet-18 student beats its ResNet-50 teacher (89.38%); the 1.6 MB TFLite model runs on Android in 100–300 ms.
- 🏆 **Champion — COMSYS Hackathon 7** (COMSYS-2026): rank #1 on the public leaderboard (0.766) for multi-script handwritten segmentation & recognition.
- 🖼️ **Top 5 Best Poster — IndiSetu Kolkata 2026:** liver-tumour segmentation on LiTS CT with a SLIC-superpixel Swin-UNet.
- 🥉 **2nd Runner-Up, Best Actian Usage — HexaFalls 2.0** (JIS University) for Legilimens.
- 🚀 **CURAA selected for the Atal Incubation Centre** cohort (2026).
- 🎓 Grade O — AICTE × EduSkills AI/ML internship · BIT Mesra Leadership Bootcamp · Oracle Cloud & Google Cloud GenAI certified.

---

## Selected work

<table>
<tr>
<td width="50%" valign="top">

### 🐾 [CURAA](https://curaapets.com)
**An AI collar that listens to what pets can't say.**
Maps a dog's vocalizations and movement to behaviour patterns — coughing, scratching, barking, sleep and activity changes — processed on the paired phone. Firmware, TinyML bio-acoustic engine, Flutter app and Cloudflare backend.

`TinyML` `Flutter` `React` `Cloudflare Workers`

</td>
<td width="50%" valign="top">

### 📡 EdgeRF
**Drone-controller identification for the edge.**
One SNR-agnostic model identifies 17 RC controllers at 99.89% (prior best 95.62%) in a 0.59 MB INT8 model at ~2 ms per CPU inference — plus a leakage-aware re-evaluation of DroneRF.

`PyTorch` `RF signal processing` `INT8` `Kaggle`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ VaaniKavach
**A bodyguard for your phone calls.**
On-device sentinel that detects synthetic voices with a distilled anti-spoofing model, flags scam psychology in Bengali & Hindi, and turns every flag into a hash-chained evidence pack.

`AASIST → TFLite` `Kotlin` `Whisper`

</td>
<td width="50%" valign="top">

### 🧠 Distillation Lab
**Shrinking giant models until they fit in your pocket.**
The research program behind the IEEE SPACE paper: progressive teacher → assistant → student distillation across CNNs and ViTs, validated on CIFAR-10, MedMNIST and a 6-class military vehicle dataset.

`PyTorch` `ViT` `Attention transfer` `ONNX`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ❤️ [HeartSense](https://github.com/workforakng/heartsense)
**Your camera can hear your heartbeat.**
Contactless heart rate, SpO₂, respiration, HRV and stress from 30 s of phone-camera video, fully offline. 1.64 BPM MAE on UBFC-rPPG.

`rPPG` `MediaPipe` `Kotlin` `Chaquopy`

</td>
<td width="50%" valign="top">

### 🎓 [Legilimens](https://github.com/Sourodyuti/Legilimens)
**A confusion radar for live classrooms.**
Students press one button when they're lost; the system returns a personalised voice explanation in seconds via hybrid BM25 + vector retrieval — fully on-prem.

`FastAPI` `WebSockets` `sqlite-vec` `Next.js`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📈 Delta Terminal
**A terminal for crypto derivatives. In Rust.**
BTC/ETH futures & options: neural-ensemble inference, options chains with Greeks/IV/OI, and a headless CLI built so AI agents can operate it. ~90 MB RAM.

`Rust` `WebSockets` `Options Greeks`

</td>
<td width="50%" valign="top">

### 🏥 SehatKhata
**India's medical records live in plastic bags. We replace the bag.**
Offline-first, voice-first PWA that turns crumpled prescriptions into a health timeline with deterministic interaction and allergy checks. Built in a 36-hour hackathon.

`Fastify` `Prisma` `NVIDIA NIM` `PWA`

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>

<br/>

| Project | Description | Stack |
|---|---|---|
| **Melt-Pool Vision** | Real-time melt-pool segmentation for directed-energy-deposition 3D printing, exported to ONNX for the edge | PyTorch, Fast-SCNN, ONNX |
| **ResumeIQ AI** | [Live](https://resumeiq-ai-9qc.pages.dev) ATS rule engine + LLM critique that scores a resume like a recruiter | Next.js, Hono, Cloudflare Workers |
| **3D Face Reconstruction** | Monocular 3D mesh from a single image at 30+ FPS, OBJ/PLY/STL export | MediaPipe, OpenCV, Open3D |
| **FinLens** | AI market-intelligence terminal for NSE/BSE with sentiment scoring and volume-anomaly alerts | FastAPI, Next.js, PostgreSQL |
| **Alpha Backtester** | Options backtesting with 30+ indicators and Kelly sizing | Python, Flask, Socket.IO |
| **VibeApp** | College social app with WebSocket chat rooms and a trust-score aggregator | Go, React Native, PostgreSQL |
| **Quantum Rx** | Drag-and-drop quantum circuit builder → IBM Quantum API | React, TypeScript, FastAPI |
| **VeriFi** | On-chain attendance & certificate verification with NFT minting | Solidity, Next.js, Web3.js |
| **Marchintosh** | Custom Arch Linux live ISO with KDE Plasma and a one-command installer | Bash, archiso |

</details>

---

## Toolbox

**ML / Vision** — PyTorch · TensorFlow · OpenCV · YOLO · Swin / ViT · SAM2 · knowledge distillation · ONNX · TensorRT · TFLite

**Edge / Hardware** — ESP32 / ESP8266 · TinyML · TFLite Micro · FreeRTOS · BLE · embedded Rust

**Full-stack** — TypeScript · React / Next.js · Flutter · Kotlin · Hono · FastAPI · Cloudflare Workers · PostgreSQL · Redis · Docker

**Systems / Quant** — Rust · Python · C++ · Go · options Greeks · market microstructure · backtesting

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Sourodyuti&show_icons=true&hide_border=true&bg_color=0d0d0f&title_color=ff4d00&icon_color=ff4d00&text_color=f2efe9&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sourodyuti&layout=compact&hide_border=true&bg_color=0d0d0f&title_color=ff4d00&text_color=f2efe9&langs_count=8" height="165"/>

<img src="https://streak-stats.demolab.com?user=Sourodyuti&hide_border=true&background=0d0d0f&ring=ff4d00&fire=ff4d00&currStreakLabel=f2efe9&sideLabels=a19d96&dates=a19d96&currStreakNum=f2efe9&sideNums=f2efe9" height="165"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff4d00,100:0d0d0f&height=100&section=footer" width="100%" />

*Read the paper Friday, ship the implementation Monday.*

</div>
