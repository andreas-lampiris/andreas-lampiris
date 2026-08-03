# Andreas Lampiris

Full-stack and AI developer based in Athens, Greece. Studying Mechanical Engineering at
**Rose-Hulman Institute of Technology** in Indiana, Class of 2030.

I build complete products end to end — the database, the API, the interface, and the machine
learning that makes them useful. Most of my work sits in medical technology: ophthalmology
screening tools, clinical data platforms, and systems that turn messy real-world input
(scanned reports, camera feeds) into structured information. These are not demos — they run
in production on Raspberry Pi hardware, a Mac Mini server, and the cloud, and clinicians use
them.

**Portfolio: [andreaspataeipaulo.github.io](https://andreaspataeipaulo.github.io)**

## What I work on

### Medical technology — DDART

Research developer for DDART, an ophthalmology technology group.

- **Unified patient database** — aggregates records from several clinical sources every 60
  seconds, keyed by national health ID. On-device LLM analysis (Ollama / phi-4), PubMed
  literature search, biometrics, visual-acuity and defocus-curve analysis, and deterministic
  clinical findings.
- **Fundus screening study platform** — a RETFound-based multi-label classifier for glaucoma,
  diabetic retinopathy and AMD, wrapped in a grading workflow where clinicians label images
  and build the training set as they work.
- **Clinical OCR pipeline** — parses scanned Alcon biometry reports (Tesseract + pdf2image)
  into structured records that flow straight into the database.
- **Dry-eye assessment app** — doctor-facing clinical chat and an AI patient-file generator
  over a locally hosted language model.
- **Screening and information sites** — including a preschool visual-acuity screening app
  deployed to Raspberry Pi behind an Nginx subpath.

### Other projects

- **EyeScreen** — full-stack ophthalmology screening web app running five clinical vision
  tests with real-time MediaPipe computer vision.
- **SnapNav** — navigate websites by hand gesture, driven by live hand-landmark tracking.
- **Margipan** — bilingual (Greek / English) Next.js site for a bakery in Vouliagmeni, live on
  a custom domain.

## Engineering beyond software

I co-founded my school's FIRST Robotics team and led the shooter and intake subsystems,
redesigning the intake from roughly 50 parts down to 20 while making it more reliable.
Mechanical design is where I'm headed at Rose-Hulman; software is how I got there.

## Tools

| | |
|---|---|
| **Languages** | Python, JavaScript / TypeScript, Swift, SQL |
| **Frontend** | Vue 3, Next.js / React, Tailwind CSS, Vite |
| **Backend** | FastAPI, SQLAlchemy, SQLite / PostgreSQL |
| **AI & vision** | PyTorch, RETFound, MediaPipe, Ollama (local LLMs), Tesseract OCR |
| **Infrastructure** | Raspberry Pi, systemd, Nginx, Tailscale, Vercel, GitHub Pages |

## Contact

- Email: [andreaslab56@gmail.com](mailto:andreaslab56@gmail.com)
- Portfolio: [andreaspataeipaulo.github.io](https://andreaspataeipaulo.github.io)

Most of my repositories are private — they contain clinical software and patient-facing
systems. Happy to walk through any of it on request.
