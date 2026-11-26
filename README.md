# Andreas Lampiris

Electrical Engineering student at **Rose-Hulman Institute of Technology** (Class of 2030, GPA 4.0),
from Athens, Greece.

I build complete products end to end — the database, the API, the interface, and the machine
learning that makes them useful. Most of my work is medical technology: ophthalmology screening
tools, clinical data platforms, and research-study software. These are not demos — they run in
production on Raspberry Pi hardware, a Mac Mini server, and the cloud, and clinicians use them
every day. At Rose-Hulman I also write embedded firmware for a Formula SAE electric car and do
computational research on quantum-sensor defects.

**[Read the full engineering write-up](https://iddartech.med.duth.gr/ddart/engineering/)**
— how the screening model was trained on 487,521 retinal images, what it actually scores on
hospitals it has never seen, and the two experiments that failed.
&nbsp;·&nbsp; **[Resume (PDF)](Andreas_Lampiris_Resume.pdf)**

## In production

Research developer for DDART, an ophthalmology technology group in Greece. I am the sole
developer of the platform below.

| System | What it does | Used by | Scale | Code |
|---|---|---|---|---|
| **Unified patient database** | Merges biometry, retinal photographs, vision exams and questionnaires from four systems into one record keyed by national health ID; a local LLM drafts cataract-surgery reports with cited PubMed evidence | 20 ophthalmologists at a university hospital and six health centres | ~500 patients | [public copy](https://github.com/andreas-lampiris/ddart-patient-database) |
| **Fundus screening study** | RETFound (ViT-L) referral model for glaucoma, diabetic retinopathy and AMD, inside a blinded expert-grading workflow | 32 researchers, six health centres | 2,978 expert reviews of 456 images · 81% AI–expert agreement (preliminary) · AUC 0.81–0.86 at ~90% specificity on unseen hospitals | [public copy](https://github.com/andreas-lampiris/ddart-fundus-screening) |
| **ddartBOT – Dry Eye Study** | Study platform and AI clinical assistant: research fellows enrol participants and ask ddartBOT about any of them, by text or voice | 25 research fellows | 1,300+ participants | private |
| **ddartBOT dry-eye assistant** | Doctor-facing dry-eye chat and AI patient-file generator over a locally hosted LLM | Clinicians | — | [public copy](https://github.com/andreas-lampiris/ddart-dryeye-assistant) |
| **DDART4OS** | AI-assisted ophthalmological screening for the Primary Care Units of Greece's 4th Regional Health Authority | Primary care units | — | private |
| **Clinical OCR pipeline** | Parses scanned Alcon biometry reports (Tesseract + pdf2image) into structured records | Feeds the patient database | — | private |
| **Preschool visual-acuity screening** | Information and screening web app on Raspberry Pi behind Nginx | Screening programme | — | private |

The private systems hold clinical software and patient-facing services, so their code is not
published. In the public copies every credential is read from the environment, and no patient
record, database or model weight is included. **Code walkthroughs are available on request.**

### Other projects

- **[EyeScreen](https://github.com/andreas-lampiris/eyescreen)** — full-stack ophthalmology screening web app running five clinical vision
  tests with real-time MediaPipe computer vision.
- **SnapNav** — navigate websites by hand gesture, driven by live hand-landmark tracking.
- **Margipan** — bilingual (Greek / English) Next.js site for a bakery in Vouliagmeni, live on
  a custom domain.

## Engineering beyond software

- **Rose GPE (Formula SAE electric)** — I design PCBs in Altium Designer, write STM32 firmware for
  the steering-wheel module (driver inputs over CAN bus at 100 Hz), and work on the battery
  management system firmware.
- **Quantum-sensor research** — undergraduate researcher with Dr. Daniel Hashemi, running density
  functional theory (VASP) on Purdue's Anvil supercomputer to screen defects in AlN and ZnO.
  First author of a paper on carbon spin defects in layered GeS₂ (in preparation).
- **Robotics** — co-founded Greece's first FIRST Robotics Competition team (Best Rookie in Europe
  and Best Designed Robot, 2025). On the Greek National Robotics Team I designed the shooter and
  intake, raising accuracy from 50% to 85% and cutting the part count from 50 to 20.

## Tools

| | |
|---|---|
| **Languages** | Python, C, C++, JavaScript / TypeScript, Swift, SQL, MATLAB |
| **Frontend** | Vue 3, Next.js / React, Tailwind CSS, Vite |
| **Backend** | FastAPI, SQLAlchemy, SQLite / PostgreSQL |
| **AI & vision** | PyTorch, RETFound, MediaPipe, Ollama (local LLMs), Tesseract OCR |
| **Embedded & hardware** | STM32, ESP32, CAN bus, ThreadX (RTOS), Altium Designer, SolidWorks, Fusion 360 |
| **Infrastructure** | Raspberry Pi, systemd, Nginx, Tailscale, Vercel, GitHub Pages |
| **Scientific computing** | Density functional theory (VASP), HPC job workflows |

## Contact

- Email: [andrylab56@gmail.com](mailto:andrylab56@gmail.com)
- LinkedIn: [andreas-lampiris](https://www.linkedin.com/in/andreas-lampiris-6a7720366/)
