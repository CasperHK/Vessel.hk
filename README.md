# Vessel.hk 🇭🇰

> **Vessel.hk** is a high-performance, professional biomedical and clinical science discussion platform built specifically for Hong Kong’s medical researchers, clinicians, bioinformaticians, and biomedical engineering professionals.

---

## 🔬 Vision & Core Philosophy

In Latin and biological contexts, a **vessel** (血管 / 導管 / 載體) represents the conduit of life, fluid dynamics, and cellular transport. **Vessel.hk** serves as the digital conduit for Hong Kong's biomedical community—bridging wet-lab research, clinical translation, bioinformatics, and modern health-tech engineering.

The platform is engineered to foster rigorous, evidence-based, data-driven discussions, moving away from fragmented social media noise and toward structured academic and clinical discourse.

---

## 🛠️ Technology Stack (Grit Framework)

Vessel.hk is powered by **Grit**, leveraging a robust, high-performance, and type-safe architecture:

* **Frontend**: **React** (with Vite & Tailwind CSS) delivering a lightning-fast, minimalist, and distraction-free academic reading/writing experience.
* **Backend**: **Go** (utilizing high-concurrency routing and clean architecture patterns) for blazing-fast API response times and real-time discussion streaming.
* **Database & Search**: **PostgreSQL** for relational data integrity (users, papers, threaded discussions) paired with advanced indexing for sub-millisecond biomedical terminology search.
* **Infrastructure**: Containerized with **Docker Compose**, ready for deployment on high-availability cloud nodes or local bare-metal clusters.

---

## 📂 Project Structure

```text
vessel-hk/
├── api/                  # Go Backend (Controllers, Services, Models, Router)
│   ├── cmd/server/       # Application entrypoint
│   ├── internal/         # Business logic, database migrations, auth
│   └── go.mod
├── web/                  # React Frontend (Vite + Tailwind CSS)
│   ├── src/
│   │   ├── components/   # Reusable UI components (Threads, Markdown Editor)
│   │   ├── pages/        # Route views (Feed, Topic Detail, Profile)
│   │   └── App.tsx
│   └── package.json
├── docker-compose.yml    # Local development orchestration
└── README.md

```

---

## 🗂️ Core Discussion Modules

1. **Frontier Biomedicine (`/frontiers`)**
* CRISPR gene editing, stem cell therapies, immunotherapy breakthroughs, and synthetic biology.


2. **Clinical Translation & MedTech (`/clinical`)**
* Medical AI diagnostics, biosensors, medical device R&D, and local clinical trial insights.


3. **Bioinformatics & Big Data (`/bioinformatics`)**
* Genomic sequencing pipelines (NGS, single-cell RNA-seq), AlphaFold protein modeling, and open medical datasets.


4. **Local R&D & Regulations (`/policy-hk`)**
* HMRF (Health and Medical Research Fund) grants, IRB/ethics review navigation, and Hong Kong healthcare regulations.


5. **Academia & Career (`/academia`)**
* Postgraduate admissions (HKU, CUHK, PolyU), postdoc opportunities, and biotech industry career paths in HK and the Greater Bay Area.



---

## 🚀 Getting Started (Local Development)

### Prerequisites

* [Docker & Docker Compose](https://www.docker.com/?utm_source=gemini)
* [Go](https://golang.org/?utm_source=gemini) (v1.22+)
* [Node.js](https://nodejs.org/?utm_source=gemini) (v20+) & pnpm/npm

### 1. Clone the Repository

```bash
git clone https://github.com/your-org/vessel-hk.git
cd vessel-hk

```

### 2. Start Infrastructure (PostgreSQL)

```bash
docker-compose up -d db

```

### 3. Run Backend (Go)

```cd api
go mod download
go run cmd/server/main.go

```

*(Backend will start on `http://localhost:8080`)*

### 4. Run Frontend (React)

```bash
cd web
npm install
npm run dev

```

*(Frontend will start on `http://localhost:5173`)*

---

## 🔒 Security & Professional Verification

To maintain high academic and clinical integrity:

* **Optional Institutional Verification**: Users can verify their status using local university (`.edu.hk`) or Hospital Authority / clinical email domains to receive a verified badge.
* **Strict Evidence Policy**: Discussions in clinical and bioinformatics sections encourage DOI linking and dataset citations.

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](https://www.google.com/search?q=LICENSE&utm_source=gemini) file for details.

---

*Built with ❤️ for the Hong Kong Biomedical Research Community.*
