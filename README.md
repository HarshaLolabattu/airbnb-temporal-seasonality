# Temporal Airbnb Seasonality and Modeling

**Course:** EAS 510 – Basics of AI  
**Student Name:** Harsha Lolabattu  
**UBIT Number:** 50682313  

---

## Project Overview
This project analyzes seasonal patterns in Airbnb nightly prices and booking probability using InsideAirbnb calendar data. A large-scale night-level panel dataset is constructed by combining listing attributes with daily availability and pricing information across multiple U.S. cities and time snapshots. The project explores seasonality, builds predictive models, and evaluates performance using both tree-based methods and neural networks.

---

## Repository Contents
- `airbnb_temporal_modeling.ipynb` — Final notebook containing all analysis, models, results, and discussion
- `requirements.txt` — Python dependencies required to run the notebook
- `images/` — TensorBoard screenshots used in Part 4 of the analysis

---

## Data Source (InsideAirbnb)
The data used in this project comes from **InsideAirbnb**. The following cities and snapshot dates were analyzed:

- **Austin:** 2024-12-14, 2025-03-06  
- **Chicago:** 2024-12-18, 2025-03-11  
- **Santa Cruz:** 2025-03-28, 2025-12-31  
- **Washington, DC:** 2025-03-13, 2025-12-18  

**Note:** Raw CSV files are not included in this repository in accordance with assignment instructions. Users should download the `listings.csv` and `calendar.csv` (or `.csv.gz`) files directly from InsideAirbnb.

---

## Expected Data Folder Structure
When running the notebook locally or in Google Colab, the data should be organized as follows:

airbnb_data/
austin_2024-12-14/
listings.csv.gz
calendar.csv.gz
austin_2025-03-06/
listings.csv.gz
calendar.csv.gz
chicago_2024-12-18/
listings.csv.gz
calendar.csv.gz
chicago_2025-03-11/
listings.csv.gz
calendar.csv.gz
santa_cruz_2025-03-28/
listings.csv.gz
calendar.csv.gz
santa_cruz_2025-12-31/
listings.csv.gz
calendar.csv.gz
washington_dc_2025-03-13/
listings.csv.gz
calendar.csv.gz
washington_dc_2025-12-18/
listings.csv.gz
calendar.csv.gz
