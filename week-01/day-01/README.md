# Day 01 — AI & ML Environment Setup & Jupyter Workflow
**Week 1 | Phase 1: Python & Data Science Foundations | July 20, 2026**

## 🛠️ What I Did
- Overviewed Phase 1 program structure and daily expectations for the AI & ML track
- Created and activated a Python virtual environment (`.venv`) using Git Bash
- Installed core data science dependencies (`numpy`, `pandas`, `matplotlib`, `jupyter`)
- Created a Jupyter Notebook (`week1_setup.ipynb`) combining Markdown and executable code cells
- Executed a setup verification script to confirm installed library versions
- Generated `requirements.txt` to ensure a reproducible environment[cite: 1]
- Configured `.gitignore` and committed all Day 1 deliverables to GitHub[cite: 1]

## 💻 Code / Commands
```bash
# Environment Creation & Activation (Git Bash)
python -m venv .venv
source .venv/Scripts/activate

# Package Installation & Verification
pip install numpy pandas matplotlib jupyter
jupyter notebook

# Freezing Dependencies
pip freeze > requirements.txt