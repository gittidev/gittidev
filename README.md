## 👋 Boram Park

**Software Developer · Vision AI Engineer**

Career path: **nursing → disaster-safety administration → clinical research → software**.
I work end-to-end — data pipelines, model training, backend services, and frontend.

- 🎓 Korea National Open University — Computer Science (senior) · Chosun University — B.S. in Nursing
- 🏫 Samsung Software Academy for Youth (SSAFY)
- ✍️ [Velog](https://velog.io/@qhfka961/posts)

---

### 🔭 Currently Working On

**Drone & LiDAR remote sensing** — semantic segmentation of 2 cm/px aerial imagery and 3D voxel mapping from LiDAR point clouds, covering the whole loop from data pipeline and labeling to training, inference, and web visualization.

| Area | What I've used |
|------|----------------|
| Segmentation | U-Net (ResNet34 encoder) with multi-channel input (RGB + LiDAR height/roughness) · compared DINOv2 + LoRA and ConvNeXt encoders · CE + Dice + area-consistency losses |
| Labeling | SAM2 auto-masks for label drafts · custom brush labeling tool |
| 3D / Geo | LiDAR point clouds (laspy, PDAL) · photogrammetry (OpenDroneMap) · multispectral imagery · GeoTIFF / UTM rasters (rasterio) · PostGIS |
| MLOps | MLflow experiment tracking · Dockerized GPU training & inference workers |
| Visualization | three.js / WebGL voxel rendering · MapLibre GL |

---

### 🏥 Previous Work — Healthcare Vision AI (2025 – 2026)

| Product | What it is | Stack |
|---------|------------|-------|
| **NEURIXIA** | Desktop app for cerebral microcirculation analysis. Built **full-stack in ~2 months** from kickoff to delivery (model training · backend · desktop). nnU-Net 2D segmentation + ONNX Runtime real-time inference, 26 dual-phase microcirculation metrics, ROI tracking · batch queue · history comparison | Electron · React · ONNX Runtime · nnU-Net · FastAPI |
| **BREATH AI** | Camera-based CPR quality analysis (A: airway / B: BVM / C: compressions) that replaces costly sensor equipment with vision, with a de-identified wireframe mode. Worked on the **BVM pipeline** — aligning manikin sensor packets with on-screen vision signals as time series to train an LSTM; edge targets Jetson Orin Nano · DEEPX NPU | RT-DETR · YOLO · Pose · LSTM · PyTorch · Jetson · DEEPX |
| **Company website & dispatch UI** | Website for a smart ambulance dispatch company (KR/EN/JP · responsive · SEO), dispatch dashboard UI/UX redesign, and mobile app UI improvements | Vue 3 · TypeScript · Tailwind · Pinia |

---

### 🧰 Tech Stack

**Languages**
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=fff)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=000)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=fff)

**Frontend / Desktop**
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=000)
![Next.js](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=fff)
![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-38B2AC?style=flat&logo=tailwind-css&logoColor=fff)
![Electron](https://img.shields.io/badge/-Electron-47848F?style=flat&logo=electron&logoColor=fff)

**AI / Vision**
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/-ONNX%20Runtime-005CED?style=flat&logo=onnx&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/-MediaPipe-0097A7?style=flat&logo=google&logoColor=white)

**Edge AI / Hardware**
![Jetson Orin Nano](https://img.shields.io/badge/-Jetson%20Orin%20Nano-76B900?style=flat&logo=nvidia&logoColor=white)
![DEEPX NPU](https://img.shields.io/badge/-DEEPX%20NPU-1B1B1F?style=flat&logoColor=white)

**Backend / Real-time / Infra**
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white)
![WebSocket](https://img.shields.io/badge/-WebSocket-010101?style=flat&logo=socketdotio&logoColor=white)
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

### 📜 Certifications

**NVIDIA DLI — Building Real-Time Video AI Applications** (2026) · **NVIDIA DLI — Getting Started with Deep Learning** (2026) · **Engineer Information Processing** (2025) · **Linux Master Level 2** (2025) · **NCA** Naver Cloud Certified Associate (2025) · **SQLD** SQL Developer (2025) · **Engineer Construction Safety** (2018) · **Computer Specialist in Spreadsheet & Database Level 1** (2018) · **Registered Nurse License** (2017)

---

### 🎓 Teaching · Mentoring

- **Dongil Mirae High School** — Instructor, *AI Project* course (Dec 2025 – Feb 2026, high school–university linkage program)
- **High School–College Linked Curriculum Council** — Advisory committee member (appointed by the President of Gwangju Health University, May 2026 – May 2027)
- **Chonnam National University SW-Centered University Program** — Winter/summer internship mentor
- **SSAFY 14th cohort** — Industry mentor for company-linked projects
- **RISE Program** — Industry-side coordinator (Gwangju Health University · Christian College of Nursing consortium)

---

### 🩺 Earlier — Clinical Research

**Clinical Research Coordinator (CRC)**, Chonnam National University Hospital Clinical Trial Center (Feb 2021 – Jan 2023) · managed multiple multi-center trials in immunology, dermatology, respiratory, and vaccines (screening · dosing · safety reporting).

---

### 🚀 Projects

| Project | Description | Link |
|---------|-------------|------|
| **Ttalkak** | One-click deployment desktop app integrated with GitHub — auto-generated Dockerfiles · real-time container monitoring · blockchain rewards for resource providers | [GitHub](https://github.com/ttalkak) |
| **Toudeuk** | Real-time reward click game on a Redis-based high-concurrency architecture *(Team Lead)* | [GitHub](https://github.com/gittidev/Toudeuk) |
| **StoryBoat** | Real-time collaborative storytelling with WebRTC P2P · Yjs (CRDT) sync · ReactFlow *(Team Lead)* | [GitHub](https://github.com/gittidev/Storyboat) |
| **CRAM** | WebSocket-based real-time CS quiz platform | [GitHub](https://github.com/CS-Quiz/CS-Quiz) |

---

### 📊 GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=gittidev&show_icons=true&hide_border=true&theme=default" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gittidev&layout=compact&hide_border=true&theme=default" height="160" />
</p>
