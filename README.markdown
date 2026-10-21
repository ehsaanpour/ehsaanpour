<div align="center">

<!-- Animated Typing Header -->
<a href="https://github.com/ehsaanpour">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=00E5FF&center=true&vCenter=true&multiline=true&repeat=true&width=850&height=100&lines=Ehsan+Ehsanpour;Broadcast+%26+Streaming+Systems+Engineer;Python+%7C+TypeScript+%7C+FastAPI+%7C+NDI+%26+RTMP+Automation" alt="Typing SVG" />
</a>

<p align="center">
  <a href="https://ehsan.cc.cc"><img src="https://img.shields.io/badge/🌐_Portfolio-ehsan.cc.cc-00E5FF?style=for-the-badge&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/ehsaanpour"><img src="https://img.shields.io/badge/LinkedIn-ehsaanpour-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://t.me/ehsaanpour"><img src="https://img.shields.io/badge/Telegram-@ehsaanpour-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <img src="https://komarev.com/ghpvc/?username=ehsaanpour&label=Profile%20Views&color=00E5FF&style=for-the-badge" alt="Profile Views" />
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

</div>

## 📡 About Me

I am a **Broadcast & Software Engineer** specializing in bridging professional **broadcasting infrastructure** with modern **web architectures**. From low-latency **NDI screen capture** and **RTMP ingest pipelines** to **VDR media transfer automation** and full-scale **studio control systems**, I build high-reliability tools for live production workflows.

- 🎥 **Broadcast Engineering:** NDI®, RTMP/RTMPS, HLS, WebRTC, VDR/FTP ingest, OBS Studio automation, and live stream orchestration.
- ⚙️ **Backend & Systems:** Designing resilient APIs, real-time control planes, and scheduling systems with **Python (FastAPI)** and **TypeScript**.
- 📊 **Data & Automation:** Applying data science and scripting to streamline studio operations, shift management, and media pipelines.

---

## 🎛️ Broadcast & Live Production Architecture

```mermaid
flowchart LR
    subgraph Sources["🎥 Studio & Capture Sources"]
        A[NDI Screen Capture]
        B[Camera / VDR Ingest]
        C[OBS Studio / vMix]
    end

    subgraph Core["⚙️ Control & Automation Core"]
        D[Studio Management System<br/>TypeScript]
        E[NegahkadehStream Engine<br/>Python]
        F[VDR_FTP Automated Transfer]
    end

    subgraph Distribution["📡 Live Distribution & Playout"]
        G[InstaLiveCLI<br/>RTMP Bridge]
        H[Multi-CDN / Live Playout]
        I[Shift & Crew Scheduler<br/>FastAPI]
    end

    A -->|Low-Latency NDI| D
    B -->|FTP / Media Sync| F
    F --> E
    C -->|RTMP Ingest| G
    D --> E
    E --> H
    G -->|RTMPS Stream| H
    I -.->|Operations Sync| D
