# 🧠 Topcoder Google Colab Template

**Reusable Google Colab template for Topcoder competitions with a clean, copy-per-challenge workflow.**

This repository is a **read-only master template** designed to be copied and customized for each Topcoder competition using **Google Colab**.

---

## ⚠️ IMPORTANT — Read This First

**Do NOT work directly in this repository.**

This repo is a **template**, not a workspace.

For every new competition, you must create a **new repository copy** using GitHub’s  
🟩 **Use this template** button.

---

## ✅ What this repository is for

- A **clean, reusable master workflow**
- Running **Topcoder competitions in Google Colab**
- Standardizing setup, training, inference, and submission
- Avoiding accidental edits to your master notebook

---

## ❌ What this repository is NOT for

- ❌ Submitting directly to Topcoder
- ❌ Experimenting or training models
- ❌ Storing datasets or outputs
- ❌ Keeping competition-specific hacks

Think of this repo as a **blueprint**, not a workbench.

---

## 🚀 How to use this template (REQUIRED)

### Step 1 — Create a competition-specific copy
1. Open the **main page** of this repository
2. Click the green **🟩 Use this template** button (top-right)
3. Create a new repo named something like:
tc-crater-rims-2026

This creates a **clean, editable copy** with no shared history.

---

### Step 2 — Open the notebook in Google Colab

#### Option A: From Colab UI
1. Go to https://colab.research.google.com
2. File → Open notebook
3. Select the **GitHub** tab
4. Paste the URL of your new competition repo
5. Open `notebook.ipynb`

#### Option B: Direct link
https://colab.research.google.com/github/<USERNAME>/<REPO>/blob/main/notebook.ipynb

---

### Step 3 — Save a working copy in Drive (IMPORTANT)
When the notebook opens in Colab:

File → Save a copy in Drive

✅ Work only in the **Drive copy**  
❌ Do NOT edit the GitHub-hosted notebook directly

---

## 📁 Repository structure

./<br>
├── LICENCE # Legal clarity<br>
├── README.md # This file<br>
├── requirements-colab.txt # Python dependencies for the colab environment<br>
├── requirements.txt # Python dependencies<br>
├── topcode_notebook.ipynb # Main Colab notebook (template)<br>
├── .gitignore # a file that contain what should not be comitted to git<br>
├── data/ # Intermediate files (Drive/local only)<br>
├── data_raw/ # DO NOT COMMIT DATA<br>
├── doc/ # documentation files e.g. AI & compliance documents<br>
├── models/ # Trained models (optional)<br>
├── notebooks/ # data retrieval methods using colab notebooks<br>
├── outputs/ # Predictions + submission ZIP<br>
└── src/ # Python helper modules<br>

### Rules
- ❌ Do not commit large datasets
- ❌ Do not commit submission ZIPs
- ✅ Keep code generic and reusable
- ✅ Use Google Drive for data and outputs

---

## ⚙️ What to change per competition

Inside `notebook.ipynb`, **only edit the CONFIG section at the top**:

- Competition name
- Input data paths
- Output paths
- Model parameters
- Random seed
- Submission format options

Everything else should remain unchanged.

---

## 📦 Submission output

The notebook should automatically generate:

outputs/<br>
&nbsp;&nbsp;&nbsp;&nbsp;└── submission/<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── submission_<timestamp>.zip

This ZIP is what you upload to **Topcoder**.

---

## 🔁 Recommended workflow (TL;DR)

1. Click **Use this template**
2. Open notebook in **Google Colab**
3. Save a copy to **Google Drive**
4. Mount Drive and set paths
5. Run all cells
6. Download submission ZIP
7. Submit to Topcoder

---

## 🧪 Reproducibility notes

- Fix random seeds where possible
- Log library versions
- Keep inference deterministic

This helps with:
- Debugging
- Leaderboard iteration
- Scientific challenges

---

## 🧼 Keeping the master template clean

If you improve the workflow:
1. Copy **general improvements only** back into this template repo
2. Do NOT copy competition-specific logic
3. Keep this repo **minimal and reusable**

---

## 🚫 Common mistakes to avoid

- ❌ Clicking **Fork** instead of **Use this template**
- ❌ Editing the GitHub notebook directly in Colab
- ❌ Uploading datasets to GitHub
- ❌ Mixing multiple competitions in one repo

---

## 📜 License

This project is licensed under the **MIT License**.

You are free to use, modify, and adapt this template for competitions and other projects.

---

## 📌 Final note

If something feels confusing during a competition,  
**the template needs better documentation — not a new workflow.**

Improve the template once. Reuse it forever.
