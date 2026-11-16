# Outlet Transfer Dashboard

Static dashboard for Outlet 801 inventory transfers and Square sales. Hosted on GitHub Pages.

## Weekly update

1. Replace the three NetSuite CSVs (`DC to Outlet.csv`, `In802.csv`, `802 ITem receceipts.csv`) and `Outlet sales performance.xlsx` in this folder.
2. Run `python scripts/build_outlet_dashboard.py` to rebuild `index.html`.
3. Run `python scripts/publish_to_github.py` to commit and push `index.html`. GitHub Actions redeploys Pages within a few minutes.

Only `index.html` and the deploy files are published. Source CSV/XLSX files stay local (see `.gitignore`).
