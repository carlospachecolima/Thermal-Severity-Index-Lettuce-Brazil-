 Thermal Severity Index — Lettuce (Brazil)

This repository gathers maps of the **thermal severity index for lettuce crops (Lactuca sativa L.)** in Brazil, based on the regional downscaling **ETA–HadGEM2-ES**. Figures are organized by season, time period, and climate scenario (RCP 4.5 / RCP 8.5).

Repository Structure
- `data/` — JPEG maps organized by **season** (`winter/`, `autumn/`, `spring/`, `summer/`) and **time period**:
  - `historico/` = historical baseline  
  - `curto_prazo/` = near future (Present–2040)  
  - `medio_prazo/` = mid-century (2041–2070)  
  - `longo_prazo/` = end of century (2071–2100)
- `docs/` — documentation (methodology, license).
- `scripts/` — reserved space for reproducible workflows (PyQGIS/processing).

Climate Modeling
- Model:** ETA–HadGEM2-ES (CMIP5)  
- Scenarios: RCP 4.5 and RCP 8.5  
- Time horizons:** historical baseline, Present–2040, 2041–2070, 2071–2100  
- Seasons covered: winter, autumn, spring, and summer  

Suggested Citation
Citation as Zenodo repositorie. 

How to Contribute
Pull requests are welcome — for example, to add new crops, models, or future scenarios. See `docs/metodologia.md` for details on the methodological basis.

License
All content (maps and texts) is available under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license. See `docs/licenca.md`.

