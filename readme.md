# Financial Analysis of Apple, Microsoft, and Tesla (2021–2023)

**Author:** Costas Pinto  
**Client:** Global Finance Corp (GFC)  
**Team:** BCG GenAI Consulting

---

## Overview

This project performs a structured, exploratory financial analysis on the 10-K reports of Apple, Microsoft, and Tesla from 2021 to 2023. Using Python and libraries like `pandas`, `matplotlib`, and `seaborn`, the project derives growth metrics, visualizes key trends, and prepares data for integration with AI-powered financial tools.

---

## Key Features

- Cleaned and validated financial dataset
- YoY (Year-over-Year) growth rate calculations
- QuantumBlack-inspired dark theme visualizations
- Professional-quality charts with annotations and minor/major gridlines
- Exportable charts and processed CSVs
- Final executive summary suitable for integration into reports or chatbot systems

---
![alt text](image.png)

## Project Structure

```

FINANCIAL\_ANALYSIS\_EDA/
├── datasets/                         # Raw and processed CSV files
│   └── processed\_financial\_data.csv
├── plots/                            # Auto-saved financial trend graphs
│   └── \*.png
├── reports/                          # Final analysis summary (PDF/HTML)
│   └── financial\_analysis\_quantumblack.pdf
├── venv/                             # Python virtual environment
├── .gitignore
├── financial\_analysis\_quantumblack.ipynb  # Main EDA notebook
├── financial\_analysis\_quantumblack.html   # Exported notebook
├── readme.txt
└── requirements.txt

````

---

## How to Run

### 1. Create and activate virtual environment
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```bash
jupyter notebook financial_analysis_quantumblack.ipynb
```

> Or use VSCode with Jupyter support.

---

## Dataset Notes

The dataset includes:

* `Total Revenue`, `Net Income`, `Total Assets`, `Liabilities`, and `Operating Cash Flow`
* Derived growth metrics: Revenue Growth %, Net Income Growth %, etc.

---

## Visualizations

Visual charts include:

* Revenue, Net Income, Assets & Liabilities trend (2021–2023)
* Year-over-Year growth charts
* Clean, dark-grid style visual theme for professional presentation

---

## Use Case

* Can be integrated into an AI-powered chatbot project (e.g., GFC Financial Chatbot)
* Ready to be included in investor dashboards, presentations, and reporting tools

---

## License

MIT License

---

## Contact

Costas Pinto
[GitHub: MrCoss](https://github.com/MrCoss)
Email: [costaspinto312@gmail.com](mailto:costaspinto312@gmail.com)

````

---

### `requirements.txt`

```txt
pandas>=1.5.3
matplotlib>=3.7.1
seaborn>=0.12.2
numpy>=1.24.3
````

> Optional:

```
jupyter
notebook
