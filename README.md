# 🌍 Data Analysis of Hardware Environmental Impact

## Overview

This project investigates the environmental impact of hardware devices by analyzing their lifecycle emissions. Using statistical techniques, we identify key factors—such as weight, screen size, and manufacturer—that contribute to greenhouse gas (GHG) emissions in different lifecycle stages: manufacturing, transport, use, and disposal.

Designed with stakeholders like municipalities, manufacturers, and investors in mind, the analysis supports data-driven decisions for sustainability, urban logistics, and e-waste policy.

---

## Objectives

- Quantify the influence of physical and categorical device characteristics on emissions.
- Highlight emission disparities between manufacturers and usage categories.
- Support sustainable manufacturing, logistics, and recycling policy improvements.

---

## Variables and Entities

### 📊 Dataset Variables

| Variable                | Type         | Subtype     |
|-------------------------|--------------|-------------|
| manufacturer            | Categorical  | Nominal     |
| name                    | Categorical  | Nominal     |
| category                | Categorical  | Nominal     |
| gwp_total               | Numerical    | Continuous  |
| gwp_use_ratio           | Numerical    | Continuous  |
| yearly_tec              | Numerical    | Continuous  |
| lifetime                | Numerical    | Discrete    |
| use_location            | Categorical  | Nominal     |
| report_date             | Categorical  | Ordinal     |
| gwp_error_ratio         | Numerical    | Continuous  |
| gwp_manufacturing_ratio | Numerical    | Continuous  |
| weight                  | Numerical    | Continuous  |
| assembly_location       | Categorical  | Nominal     |
| screen_size             | Numerical    | Continuous  |

### 👥 Entities and Related Variables

| Entity         | Variables Used |
|----------------|----------------|
| **Municipalities** | `lifetime`, `use_location`, `gwp_total`, `gwp_use_ratio`, `yearly_tec`, `category`, `weight`, `assembly_location` |
| **Manufacturers**  | `manufacturer`, `name`, `gwp_manufacturing_ratio`, `gwp_error_ratio`, `weight`, `screen_size`, `lifetime`, `gwp_total` |
| **Investors**      | `use_location`, `lifetime`, `weight`, `category`, `gwp_total`, `gwp_use_ratio`, `yearly_tec` |

---

## Key Analyses

- 🔍 **Correlation Tests**: Investigated the impact of device weight, screen size, and lifetime on emissions.
- 📊 **ANOVA and Chi-Square Tests**: Compared emission levels across manufacturers and usage categories.
- 🧠 **Sustainability Insights**: Identified actionable improvements for eco-friendly design and policies.

---

## Technologies Used

- **Python 3**
- **pandas**, **matplotlib**, **seaborn**
- **Jupyter Notebook**
- **Statistical Tests**: Pearson, Spearman, Kendall, ANOVA, Chi-Square

---

## Project Structure

```
Data-Analysis-of-Hardware-Environmental-Impact/
├── data/                   # Raw and processed datasets
├── notebooks/              # Analysis notebooks
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── .gitignore
```

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/0Londero/Data-Analysis-of-Hardware-Environmental-Impact.git
   cd Data-Analysis-of-Hardware-Environmental-Impact
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## Contributors

- [Otávio Londero](https://github.com/0Londero): Manufacturers  
- [Amir Oliveira](https://github.com/aloblack): Municipalities

---

## License

This project is open source and available under the [MIT License](./LICENSE.txt).  
Feel free to use, modify, and cite it in academic or industrial applications.
