# Morphological Parameter Analysis of DES and DESI Galaxies

This repository contains the code used to study the morphological parameters of galaxies across different astronomical surveys, including DES DR2, DESI LS DR10, DES Y6 Gold and DES Y3 Metacal catalogs.

The goal is to investigare systematic differences in ellipticities, projected axes and position angles between catalogues, even when based on observations from the same instrument.

---

## Surveys Used

- Dark Energy Survey (DES DR2)
- DES Year 6 Gold
- DES Year 3 Metacal
- DESI Legacy Survey DR10

---

## Workflow

The work carried out during this internship can be summarized in the following steps:

1. Cross-match between astronomical catalogues using TopCat and Python-based workflows.

2. Morphological selection of galaxy sources using specific classification criteria.

3. Data cleaning and filtering of non-physiscal or problematic parameter values.

4. Recalculation and validation of morphological parameters such as:
   
   - ellipticities
   - projected axes
   - position angles

5. Comparative analysis between surveys using:

   - linear regressions
   - histograms
   - consistency checks

6. Additional comparison of photometric magnitudes between calatogues.

7. Interpretation of systematic differences between survey pipelines and parameter definitions.

---

## Results

The analysis revealed systematic differences in morphological parameters across catalogues, even when derived from the same observational instrument. These results highlight the importance of understanding the specific processing pipelines and parameter definitions of each survey before performing any comparison.

---

## File descriptions

- 'practicas_ra_dec_ejes_elipses.ipynb': Contains the study and comparisson between DES DR2 and DESI LS DR10.
- 'practicas_metacal.ipynb': Contains the study and comparisson between DES DR2 and DES Y3 Metacal, and DESI LS DR10 and DES Y3 Metacal.
- 'practicas_y6_gold.ipynb': Contains the study and comparisson between DES DR2 and DES Y6 Gold, and DESI LS DR10 and DES Y6 Gold.
- 'practicas_y6_gold_metacal.ipynb': Contains the study and comparisson between DES Y6 Gold and DES Y3 Metacal.
- 'xmatch_y6_gold.ipynb': Contains the code used in Python for the cross-match between DES DR2 and DES Y6 Gold.
- 'unir_xmatch.ipynb': Contains the code used to merge every file generated in 'xmatch_y6_gold.ipynb'

---

## Data access

- For DES DR2 and DESI LS DR10 catalogues, I downloaded the data from D. Fernández-Gil's GitHub repository: https://github.com/davfer12/Detection-of-an-orthogonal-alignment-between-parsec-scale-AGN-jets-and-their-host-galaxies
- For DES Y3 Metacal catalogue, I downloaded the data from the CosmoHub repository.
- For DES Y6 Gold catalogue, I downloaded the data from the DES Data Release File Server: https://desdr-server.ncsa.illinois.edu/despublic/y6a2_files/y6_gold/
