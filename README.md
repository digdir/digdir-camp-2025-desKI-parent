# desKI-parent

This repository serves as the parent project for the **desKI** backend and frontend applications. It uses Git submodules to manage the `desKI` (backend) and `desKI-frontend` (frontend) codebases as separate repositories.

## 🧠 What's inside

- `desKI` – FastAPI-based backend application
- `desKI-frontend` – React-based frontend application
- Shared configuration like Docker Compose for local development

## 🚀 Cloning the repository

To properly clone the repository **with submodules**, use the `--recurse-submodules` flag:

```bash
git clone --recurse-submodules https://github.com/felleslosninger/desKI-parent

