# 🔭 Identifying Spectral Lines in JWST MIRI Data

This project analyses Mid-Infrared Integral Field Unit (IFU) observations from the **JWST MIRI** instrument for the galaxy **NGC 7469**. Using publicly available FITS files, the spectral data is processed to identify and compare emission features in different regions of the galaxy.

---

## 📁 Files Included

- `Identifying Spectral Lines in JWST MIRI Data.ipynb`: Main analysis notebook.
- `Identifying_spectral_lines_in_MIRI_JWST_data.pdf`: Project brief and research questions.
- `.reg` files: DS9 region selections (not uploaded here but assumed in usage).
- Extracted CSVs and plots (optional to upload).

---

## 🚀 Project Overview

### 🔹 Objectives
- Extract spectra from defined regions in MIRI IFU cubes.
- Identify emission features in MIR spectra.
- Compare spectral lines between two regions in NGC 7469.
- Estimate pixel scale in parsecs and interpret physical size coverage.

### 🔹 Tools & Libraries Used
- Python 3.x
- `astropy`
- `matplotlib`
- `pandas`
- `regions`, `spectral_cube`, `photutils`
- DS9 & Cubeviz (offline or JWST online tools)

### 🔹 Key Analysis
- Estimation of pixel scale in arcsec/pixel → parsecs/pixel.
- Extraction of 1D spectra using DS9-defined regions.
- Identification of PAH features and atomic emission lines.
- Region-wise comparison to infer physical differences.

---

## 📌 Instructions to Run

1. Download JWST MIRI spectral cube files from the [MAST Portal](https://mast.stsci.edu/portal/Mashup/Clients/Mast/Portal.html):
   - Object: NGC 7469
   - Mission: JWST
   - Instrument: MIRI/IFU
   - Product Type: cube
   - Filter: Filenames containing `c1006_`

2. Place the FITS files and `.reg` region files in the notebook directory.

3. Run the notebook step-by-step. Make sure required Python packages are installed.

---

## 📚 Key Learnings

- How to handle JWST FITS cubes using Python.
- Basics of emission line identification in MIR spectra.
- Application of astronomy libraries like `astropy` and `spectral_cube`.
- Region-based spectral comparison and scientific reasoning.

---

## 🧠 Skills Demonstrated

1. Astrophysical data analysis  
2. Spectral data visualization  
3. FITS file manipulation  
4. Python scripting for astronomy  
5. Scientific interpretation of emission features

---

## 📎 References

- [JWST MAST Portal](https://mast.stsci.edu)
- Astropy Documentation
- Cubeviz (JWST official tool)
- DS9 Image Viewer

---

## 📬 Contact

*Prepared as part of ISA Summer School 2025*  
By **Niharika Mathur**  
Email: *niharika2mathur@gmail.com*

---

## 🌟 Acknowledgements

Thanks to the Indian Summer School for Astronomy (ISA) for the opportunity to work on real JWST data and explore extragalactic infrared spectroscopy.


