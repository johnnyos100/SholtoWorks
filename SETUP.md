# GitHub repository setup — step by step

Follow these steps to publish `github.com/johnnyos100/SholtoWorks`.

---

## 1. Prepare the repository

The repo already exists at https://github.com/johnnyos100/SholtoWorks. Since it is empty, push directly:

```bash
cd docs/swtt-token-repo
git init
git branch -M main
git add .
git commit -m "Initial commit — SWTT token list and metadata"
git remote add origin https://github.com/johnnyos100/SholtoWorks.git
git push -u origin main
