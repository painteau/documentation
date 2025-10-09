# 📘 Documentation – Simplon AIS Projects

This repository centralizes all **user documentation** for the projects developed collaboratively by the learners of the **Administrateur d’Infrastructures Sécurisées (AIS)** training program.

---

## 🎯 Purpose

Provide clear, up-to-date documentation for each project created during the training.  
Every learner is a **collaborator** on this repository and contributes to writing, reviewing, and improving user guides.

---

## 📂 Repository structure

```
/
├── project-1-name/
│   ├── README.md          → Project presentation
│   ├── installation.md    → Installation and configuration guide
│   ├── usage.md           → User guide
│   └── maintenance.md     → Technical or administration notes
├── project-2-name/
│   └── ...
└── _template/
    ├── README.md
    ├── installation.md
    ├── usage.md
    └── maintenance.md
```

Each project must follow this structure.  
The `_template/` folder serves as a model to copy when starting a new project.

---

## 🧩 Contribution rules

1. **Create a branch** for each major change.  
   Example: `doc/project-1-update-installation`
2. **Write in Markdown** (`.md`) with structured titles (`#`, `##`, `###`).
3. **Use clear and neutral English** to ensure reusability.
4. **Commit clearly** with a concise message.
5. **Peer review**: every change must be validated by at least one collaborator.

---

## 🧰 Recommended tools

- **VS Code** with *Markdown All in One*
- **GitHub Desktop** or CLI `git`
- **Grammarly** or **LanguageTool** for proofreading
- **PlantUML** or **Mermaid** for diagrams

---

## 🧑‍💻 About

This repository is collectively maintained by the **Simplon AIS – Villeurbanne** cohort.  
It promotes collaborative documentation and professional best practices.

---

## 🪄 Getting started

```bash
# Clone the repository
git clone https://github.com/<ORGANISATION>/documentation.git
cd documentation

# Create a new project folder
cp -r _template/ project-3-name
git add project-3-name
git commit -m "Add project 3 documentation structure"
git push origin main
```
