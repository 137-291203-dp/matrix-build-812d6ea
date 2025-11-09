# Multi-Platform Matrix Build with Artifacts

This repository demonstrates a GitHub Actions workflow that performs a **multi-platform matrix build** with artifact uploads.  
It runs parallel jobs for multiple Node.js versions and stores the build outputs as versioned artifacts.

### 🧠 Workflow Overview
- **Matrix Strategy:** Builds for Node.js versions 14, 16, and 18  
- **Parallel Execution:** Each build runs in parallel on `ubuntu-latest`  
- **Artifacts:** Each job uploads a unique artifact with the prefix `build-812d6ea`  
- **Identifier Step:** Includes a step named `matrix-812d6ea` for validation  

### 📂 Repository Structure
.github/
└── workflows/
└── matrix-build.yml
README.md
### 📧 Contact
**Email:** 24ds2000137@ds.study.iitm.ac.in
