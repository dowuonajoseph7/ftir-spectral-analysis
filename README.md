# FTIR Spectral Analysis: Raw vs. Calcined Bauxite

This data science project processes, cleans, and visualizes Fourier-Transform Infrared (FTIR) spectroscopy data to analyze the structural changes that occur during the calcination of bauxite.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Engineering:** `pandas` and `numpy` (for data alignment, sorting, and cleaning)
- **Data Visualization:** `matplotlib` and `ticker` (for creating publication-ready overlay plots with strict domain conventions)

## 📈 Key Features Implemented
- **Domain Convention Handling:** Automatically inverts the wavenumber axis ($4000 \rightarrow 400 \text{ cm}^{-1}$) to match physical chemistry visualization standards.
- **Signal Analysis:** Visualizes raw, noisy laboratory spectral inputs alongside smoothed trend curves to maximize peak visibility.
- **High-Resolution Export:** Automatically generates and saves a clean, 200 DPI data visualization graph (`ftir_tbk_ctbk_comparison.png`).
