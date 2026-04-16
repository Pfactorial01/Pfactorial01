# Adebayo Adeoye · Pfactorial01

**Software developer** — I build automation that ships real media, backends that survive load tests, and GPU code that stays fast where it matters.

My pinned work spans **AI video orchestration** (Sheets → LLM → TTS, images, motion, final MP4), **TypeScript** product stacks (short-form video with **Mux**), **Go** systems (**ledger APIs**, **NATS** telemetry to **TimescaleDB**), and **C++/CUDA** (**stereo depth**, image filters with **FastAPI** + a web UI). Observability is a habit: **Prometheus**, **Grafana**, **k6**, and documented benchmarks show up across repos.

---

## Pinned projects

| | |
|:---|:---|
| [**AI Video Automation Pipeline**](https://github.com/Pfactorial01/AI_Video_Automation_Pipeline) | **Google Sheets** queue → **n8n** → **OpenAI** (structured script/scenes) → TTS, image gen, I2V, music, **Creatomate** — row in, **MP4** out. |
| [**VibeFlow**](https://github.com/Pfactorial01/VibeFlow) | Short-form feed: **React + Vite**, **Express + Prisma**, **PostgreSQL**, **Redis**, **Mux** uploads & playback, JWT auth, Latest/Trending. |
| [**velocis**](https://github.com/Pfactorial01/velocis) | High-throughput **financial ledger** in **Go**: `POST /transfer`, optimistic locking, Redis balance cache, **PgBouncer**, **Prometheus**/**Grafana**, **k6** suites including cross-shard sagas. |
| [**LumenStereo**](https://github.com/Pfactorial01/LumenStereo) | Real-time **GPU** stereo (**CUDA** SGBM), calibration, ImGui viewer — tuned for VRAM and throughput vs OpenCV on Middlebury-class data. |
| [**ApexStream**](https://github.com/Pfactorial01/ApexStream) | High-frequency **F1-style telemetry**: **NATS JetStream** → Go ingest/processor → **TimescaleDB** + **Redis**, full observability stack. |
| [**gpu_image_processing**](https://github.com/Pfactorial01/gpu_image_processing) | **CUDA** Gaussian/box/Sobel pipelines, naive vs optimized kernels, **FastAPI** + browser UI, **pybind11**, Nsight-friendly workflow. |

---

## Focus areas

- **Automation & production video** — spreadsheet-driven jobs, vendor APIs, reproducible n8n workflows  
- **Backend performance** — ledgers, sharding, streaming ingestion, rate limits, hypertables  
- **GPU & vision** — stereo matching, image processing, memory hierarchy and profiling  

---

## Connect

- **X (Twitter):** [@P_factorial01](https://twitter.com/P_factorial01)

---

<sub>README synthesized from the six pinned repositories on this profile.</sub>
