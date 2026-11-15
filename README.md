# County Rainfall and Planting Advisory

Cleans hand-typed Machakos rainfall data, analyses monthly rainfall for five Kenyan counties (Nairobi, Nakuru, Kisumu, Mombasa, Machakos) with NumPy, and writes a planting advisory plus `rainfall_summary.csv`.

## How to run
1. `pip install -r requirements.txt` (also install `jupyter`).
2. Run `jupyter notebook rainfall_analysis.ipynb`.
3. Choose Kernel > Restart & Run All. The CSV is regenerated.

## Planting advisory
- Nairobi, Nakuru, Kisumu and Mombasa should plant in April-May, the two wettest consecutive months.
- Machakos should plant in November-December and use drought-tolerant seed, since it has six dry months.
- Two Machakos months (April, September) were imputed at 68 mm, so verify them with the station.
