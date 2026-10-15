# Stochastic Modelling and Risk Assessment of Aeronautical Revenue Stability

**A Monte Carlo Approach (Case Study of Lamido Aliyu Mustapha International Airport, Yola)**

Birwula Aaron Zwakas, B.Sc. Operations Research, Modibbo Adama University, Yola (2026).
Supervisor: Mr. U.B Danfulani.

This repository holds the full Python code and data used in the project. It goes with Appendices D and F of the project report.

## Files

| File | What it is |
|---|---|
| `01_main_simulation.ipynb` | Main analysis: distribution tests, real value erosion, retrospective gap, Monte Carlo validation, sensitivity analysis, scenarios S1 to S5, fan charts and sustainability indicators (Chapter 4, Sections 4.2 to 4.7) |
| `02_robustness_checks.ipynb` | Robustness and validation checks F1 to F12 (Chapter 4, Section 4.8) |
| `DATA.xlsx` | Chargeable flight records (ADR16) 2021 to 2025, with monthly and annual summaries. Airline names are replaced with codes (Operator A to F) |
| `Project_Data_Complete.xlsx` | DATA.xlsx plus NBS inflation, CBN exchange rates, Yola passenger figures and the northern airport benchmark |
| `requirements.txt` | Python packages needed |

## How to run

1. Install Python 3 and Jupyter, then run `pip install -r requirements.txt`.
2. Keep the notebooks and the Excel files in the same folder.
3. Open `01_main_simulation.ipynb` and run all cells in order.
4. For the robustness checks, open `02_robustness_checks.ipynb`, run the master setup cell first, then any check (F5 and F6 need F4 first).

All simulations use random seed 42, so the results match the report.

## Data sources

Flight records: Nigerian Airspace Management Agency (NAMA), Yola. To protect the airlines' commercial information, operator names have been replaced with codes. No calculation uses the operator name, so all results are unchanged. The original records are held by NAMA. Inflation: National Bureau of Statistics (NBS). Exchange rates: Central Bank of Nigeria (CBN). Passenger and movement figures: NBS, FAAN and press reports listed in the `Sources` sheet of `Project_Data_Complete.xlsx`.
