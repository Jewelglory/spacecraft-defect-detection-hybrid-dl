# Spacecraft Defect Detection — Hybrid Deep Learning

A deep learning project that automatically detects and classifies surface defects in industrial and aerospace components using a hybrid CNN + attention + transfer learning approach.

**Accuracy: 93.61% on the NEU Surface Defect Dataset**
**Hardware: Runs on standard CPU — no GPU needed**

---

## Paper

**Hybrid Deep Learning Framework for Automated Industrial Surface Defect Detection and Classification with Potential Aerospace Applications**

Jewel Christanand Pisse, Shekhar R.
Alliance University, Bengaluru, India — 2025

---

## Results

| Metric | Value |
|---|---|
| Overall Accuracy | 93.61% |
| Macro Precision | 0.95 |
| Macro Recall | 0.94 |
| Macro F1-Score | 0.94 |

---

## Dataset

**NEU Surface Defect Dataset** — 1800 images, 6 defect classes:
Crazing, Inclusion, Patches, Pitted Surface, Rolled-in Scale, Scratches

Download: http://faculty.neu.edu.cn/yunhyan/NEU_surface_defect_database.html

---

## How to Run

**Step 1 — Install dependencies**
```
pip install torch torchvision scikit-learn matplotlib
```

**Step 2 — Open the notebook**

Open `HDLF_runnable.ipynb` in Jupyter Notebook

**Step 3 — Update your dataset paths**

In Cell 2, change these two lines to match where you saved the dataset on your computer:
```
train_path = "your/path/to/NEU-DET/train/images"
val_path   = "your/path/to/NEU-DET/validation/images"
```

**Step 4 — Run all cells top to bottom**

---

## Files

| File | Description |
|---|---|
| `HDLF_runnable.ipynb` | Main project notebook — run this |
| `Final.pdf` | Conference paper |
| `README.md` | This file |

---

## Author

**Jewel Christanand Pisse**
PG Student — Alliance University, Bengaluru
cjewelMTECH25@stu.alliance.edu.in

Supervisor: Prof. Shekhar R., Alliance University
