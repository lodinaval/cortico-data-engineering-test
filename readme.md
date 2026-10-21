# Cortico Data Engineering Take-Home Test
**Author:** Keith Aaron R. Naval
**Date:** October 21, 2026

## Results Summary
**Successfully Linked Providers:** 47
**Ambiguous Records:** 393
**New Clinics Generated:** 3527

## Prerequisites and Installation
Python 3.8+ is required to be installed.

**1. Clone the repository (or extract the zip file):**
```bash
git clone https://github.com/lodinaval/cortico-data-engineering-test
cd Naval_Cortico_TakeHome
```

**2. Set up a virtual environment (Recommended):**
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

**3. Install the required dependencies:**
```bash
pip install -r requirements.txt
```

## Running the Code
The source code is provided as a Jupyter Notebook (`Naval_TakeHomeTest_Source.ipynb`).
1. Launch Jupyter Notebook from your terminal:
```bash
jupyter notebook
```
2. Open the `.ipynb` file in the browser interface.
3. Click **Kernel > Restart & Run All** to execute the pipeline from top to bottom.
4. The script will generate two final outputs in your directory:
   * `clinic_final.csv`
   * `provider_final.csv`

## Time Management
**Total Time Spent:** 8.5 hours