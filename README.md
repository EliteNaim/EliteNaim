<p align="center">
  <img src="assets/banner.svg" alt="SM Naim — Graduate Researcher, MS Computer Science, University of Yamanashi" width="100%">
</p>

<p align="center">
  <a href="#-publications"><img src="https://img.shields.io/badge/Publications-2-1f4fd1?style=for-the-badge" alt="2 publications"></a>
  <a href="https://scholar.google.com/citations?user=GQ3HgGEAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://data.mendeley.com/datasets/n9m5bywxwc/3"><img src="https://img.shields.io/badge/Dataset-KU--BD--Fish-22a565?style=for-the-badge" alt="KU-BD-Fish dataset"></a>
  <img src="https://img.shields.io/badge/MEXT%20Scholar-2026-0f1729?style=for-the-badge" alt="MEXT Scholar 2026">
  <a href="https://www.linkedin.com/in/sm-naim-982341251/"><img src="https://img.shields.io/badge/LinkedIn-SM%20Naim-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

## 👋 About

I'm a graduate researcher and **MS Computer Science** student at the **University of Yamanashi, Japan**, supported by the **MEXT Scholarship**. My work sits where **computer vision, explainable machine learning and edge computing** meet real problems in **agriculture and aquaculture**.

Before Japan, I completed my **BSc in Electronics & Communication Engineering** at **Khulna University** (CGPA 3.80 / 4.00, ranked 2nd) and worked as an Undergraduate Research Assistant at the university's Research & Innovation Centre.

## 🧭 Research interests

`Computer Vision` · `Explainable AI (SHAP, DiCE)` · `Metaheuristic Optimization` · `Model Compression & Edge AI` · `Mixed / Augmented Reality` · `Smart Agriculture & Aquaculture`

---

## 🔬 Current research

### Real-Time Grape Disease Detection Using Optimized Deep Learning and Wearable Mixed Reality
*MS research · University of Yamanashi · 2026 – present*

Yamanashi is one of Japan's leading grape-growing regions, and farmers need disease detection that works **in the field, in real time and hands-free**. This project builds one integrated system:

```
Smart-glasses camera (RGB) ──► Optimized CNN / Transformer ──► Edge device ──► MR overlay of diseased regions
                               (pruning · quantization ·       (low latency,    (in the wearer's
                                knowledge distillation)         no cloud)        field of view)
```

- **Models:** compare CNN- and Transformer-based detectors for grape leaf disease
- **Optimization:** pruning, quantization and knowledge distillation for real-time inference
- **Deployment:** edge-assisted inference with low dependence on cloud processing
- **Evaluation:** detection accuracy, inference latency, computational cost and field usability

| Period | Milestone |
|---|---|
| Year 1 · Q1–Q2 | Data preparation and baseline disease-detection models |
| Year 1 · Q3–Q4 | Model optimization and evaluation |
| Year 2 · Q1–Q2 | Edge deployment and integration with the wearable MR system |
| Year 2 · Q3–Q4 | Field testing in real vineyards, evaluation and refinement |

---

## 📄 Publications

**[1] Aquaculture Water Quality Classification Using XGBoost Classifier Model Optimized by the Honey Badger Algorithm with SHAP and DiCE-Based Explanations**  
**S. M. Naim**, Prosenjit Das, Jun-Jiat Tiang, Abdullah-Al Nahid  
*Water* (MDPI), 2025, 17(20), 2993 · Q1 in Aquatic Science (SCImago)

> An XGBoost classifier tuned by the Honey Badger Algorithm reached up to **98.45 %** accuracy (mean 5-fold **98.05 %**). SHAP shows which water parameters drive each prediction, and DiCE gives counterfactuals showing what would need to change to improve water quality.

[![Paper](https://img.shields.io/badge/Read%20paper-MDPI%20Water-1f4fd1?style=flat-square)](https://www.mdpi.com/2073-4441/17/20/2993)
[![DOI](https://img.shields.io/badge/DOI-10.3390%2Fw17202993-0f1729?style=flat-square)](https://doi.org/10.3390/w17202993)

**[2] Glioma Classification Using Harris Hawks-Driven Optimized Gradient Boosting Classifier Along with SHAP-Based Interpretability**  
**S. M. Naim**, Jun-Jiat Tiang, Abdullah-Al Nahid  
*International Journal of Advanced Computer Science and Applications (IJACSA)*, 2025, 16(10)

> Harris Hawks Optimization tunes a Gradient Boosting classifier for glioma classification, and SHAP makes the model's decisions interpretable.

[![Paper](https://img.shields.io/badge/Read%20paper-IJACSA-1f4fd1?style=flat-square)](https://thesai.org/Publications/ViewPaper?Volume=16&Issue=10&Code=IJACSA&SerialNo=91)
[![DOI](https://img.shields.io/badge/DOI-10.14569%2FIJACSA.2025.0161091-0f1729?style=flat-square)](https://doi.org/10.14569/IJACSA.2025.0161091)
[![EBSCO](https://img.shields.io/badge/Indexed-EBSCO-b7791f?style=flat-square)](https://openurl.ebsco.com/EPDB%3Agcd%3A13%3A5769901/detailv2?sid=ebsco%3Aplink%3Acrawler-gcd&id=ebsco%3Agcd%3A189187596&crl=c&jrnl=2158107X)

<details>
<summary><b>📑 Cite (BibTeX)</b></summary>

```bibtex
@article{naim2025aquaculture,
  title   = {Aquaculture Water Quality Classification Using XGBoost Classifier Model Optimized by the Honey Badger Algorithm with SHAP and DiCE-Based Explanations},
  author  = {Naim, S. M. and Das, Prosenjit and Tiang, Jun-Jiat and Nahid, Abdullah-Al},
  journal = {Water},
  volume  = {17},
  number  = {20},
  pages   = {2993},
  year    = {2025},
  doi     = {10.3390/w17202993}
}

@article{naim2025glioma,
  title   = {Glioma Classification Using Harris Hawks-Driven Optimized Gradient Boosting Classifier Along with SHAP-Based Interpretability},
  author  = {Naim, S. M. and Tiang, Jun-Jiat and Nahid, Abdullah-Al},
  journal = {International Journal of Advanced Computer Science and Applications},
  volume  = {16},
  number  = {10},
  year    = {2025},
  doi     = {10.14569/IJACSA.2025.0161091}
}

@dataset{naim2025kubdfish,
  title     = {KU-BD-Fish: High-Resolution White-Background and Segmented Images for Species Classification},
  author    = {Naim, S. M. and Rahman, Md Ashikkur and Das, Prosenjit and Nahid, Abdullah-Al},
  publisher = {Mendeley Data},
  version   = {3},
  year      = {2025},
  doi       = {10.17632/n9m5bywxwc.3}
}
```
</details>

---

## 🗂️ Dataset

### KU-BD-Fish: High-Resolution White-Background and Segmented Images for Species Classification
**S. M. Naim**, Md Ashikkur Rahman, Prosenjit Das, Abdullah-Al Nahid  
*Mendeley Data*, Version 3, 2025 · Khulna University · License: CC BY 4.0

> **940 high-resolution images of 26 freshwater fish species native to Bangladesh.** Each fish was photographed on its own against a white background under controlled lighting. Every image comes in two versions, the raw photo and a segmented version with the background removed, organized into per-species folders with a metadata file.

**Use it for:** species classification · segmentation · object detection · morphological analysis · biodiversity research

[![Dataset](https://img.shields.io/badge/Download-Mendeley%20Data-22a565?style=flat-square)](https://data.mendeley.com/datasets/n9m5bywxwc/3)
[![DOI](https://img.shields.io/badge/DOI-10.17632%2Fn9m5bywxwc.3-0f1729?style=flat-square)](https://doi.org/10.17632/n9m5bywxwc.3)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-1f4fd1?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

---

## 🧪 Research experience

**Undergraduate Research Assistant** · Research & Innovation Centre, Khulna University · 2025  
Machine learning, computer vision, dataset development, model optimization and explainable AI (SHAP, DiCE). Co-authored both publications and the KU-BD-Fish dataset above.

**Undergraduate research project** · Khulna University  
An integrated **IoT + AI framework for sustainable aquaculture**: real-time water-quality monitoring with embedded sensors, plus computer-vision-based fish species identification (which produced the KU-BD-Fish dataset).

---

## 🛰️ Applied research projects

| Project | Question | Methods |
|---|---|---|
| **[AquaSense](https://github.com/EliteNaim/AQUASENSE)** | Can low-cost sensors + ML give fish farmers reliable, real-time water-quality decisions? | IoT sensors · ML classification · field data from ponds in Khulna |
| **BirdsAI** | Can drone footage map roadside waste hotspots automatically? | Drone imagery · computer vision · hotspot mapping |
| **Sundarban Safeguards** | Can drones + sensors monitor a mangrove ecosystem continuously? | Autonomous drones · pH, salinity, temperature and humidity sensing |

---

## 🧰 Tools

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/XGBoost-1f4fd1?style=flat-square" alt="XGBoost">
  <img src="https://img.shields.io/badge/SHAP%20%C2%B7%20DiCE-Explainable%20AI-0f1729?style=flat-square" alt="SHAP and DiCE">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white" alt="Arduino">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

---

## 🎓 Education & academic honors

- **MS in Computer Science**, University of Yamanashi, Japan · 2026 – present
- **BSc in Electronics & Communication Engineering**, Khulna University · 2022 – 2026 · CGPA 3.80 / 4.00, ranked 2nd
- 🇯🇵 **MEXT Scholarship** (University Recommendation), Government of Japan · 2026
- 🏅 **Best Student Award 2025**, Khulna University
- 🎓 **Khulna University Merit Scholarship**, four consecutive years

---

<p align="center">
  <b>Open to research collaboration in computer vision, explainable ML and AI for agriculture.</b><br>
  <a href="https://scholar.google.com/citations?user=GQ3HgGEAAAAJ&hl=en">Google Scholar</a> · <a href="https://www.linkedin.com/in/sm-naim-982341251/">LinkedIn</a>
</p>
