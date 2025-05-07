# Confidence-interval-studies

This repository provides a **visual and conceptual walkthrough** of both parametric(analytic) and non-parametric(empirical) methods for constructing confidence intervals (CIs). It is designed as an educational resource for data science, statistics, or machine learning students who want to deeply understand the meaning, construction, and common pitfalls of CIs.

## File Structure

```bash
.
├── images/                                     # All PNG exports for markdown embedding
├── notebooks/                                  # Jupyter notebooks used to generate supporting diagrams
│   ├── 01-parametric-CI-images.ipynb
│   └── 02-non-parametric-CI-images.ipynb
│   
├── 01-parametric-confidence-interval.md        # Main Discussion
├── 02-non-parametric-confidence-interval.md    # Main Discussion
├── 03-misinterpretation-of-CI.md               # Main Discussion
├── LICENSE                                     # CC BY-NC 4.0 License
├── README.md                                   # This file
└── requirements.txt                            # Python environment dependencies
```

---

## Topics & Notes Breakdown

| Topic | File | Description |
|-------|------|-------------|
| Parametric CI (t-distribution) | `01-parametric-confidence-interval.md` | Explanation of classic CI using analytical methods |
| Bootstrap CI (resampling) | `02-non-parametric-confidence-interval.md` | Hands-on demonstration of empirical CI using bootstrapping |
| ⚠️ Misinterpretations | `03-misinterpretation-of-CI.md` | Clarifies common misunderstandings in CI interpretation |

Each markdown file pairs with a corresponding `.ipynb` notebook for visual demonstrations.

## Development & Reproduction

To run, verify, or modify this project, the following environment is recommended:

- **Python version:** 3.12.4  
- **IDE:** Visual Studio Code  
  Alternatively, you may explore the notebook interactively using **JupyterLab** or **Google Colab**.

Install the required packages using:

```bash
pip install -r requirements.txt
```

The requirements.txt file was automatically generated using pipreqs:

```bash
pipreqs . --force
```

## Learning Outcomes

By the end of this study, you’ll be able to:

- Understand the difference between parametric (t-distribution) and non-parametric (bootstrap) confidence intervals.

- Implement and visualize bootstrap resampling.

- Identify and correct common misinterpretations of CIs.

- Justify when to use analytical vs. empirical methods in real-world data analysis.

## License

This project is licensed under Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

You are free to share and adapt for non-commercial purposes, with attribution.

## Author

Alex Tian

Master of Applied Science @ University of Victoria

Specializing in Data Science & Machine Learning