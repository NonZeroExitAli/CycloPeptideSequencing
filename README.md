# Cyclic Peptide Sequencing Algorithms
This project implements and compares three algorithms for cyclic peptide sequencing using theoretical mass spectrometry data:
- **Brute Force Search**
- **Branch and Bound**
- ** Spectral Convolution Branch and Bound**
These methods simulate and identify cyclic peptide sequences from spectral convolution and theoretical mass spectra matching.
---
## Project Structure
- `Brute_Force_Cyclicpeptides.ipynb`: Implements a naive brute-force approach to generate and score all possible cyclic peptide sequences.
- `Branch_and_Bound_Cyclicpeptides.ipynb`: A more efficient algorithm that builds peptide candidates iteratively and prunes unpromising ones.
- `Convolution_Branch_and_Bound_Cyclicpeptides.ipynb`: Combines spectral convolution with branch-and-bound to enhance speed and precision by restricting the amino acid mass choices.
—
## Data sets
Experimental mass spectrometry (MS) spectrum data for Pseudacyclin A, stored in the Global Natural Products Social Molecular Networking (GNPS) database. It includes fragment mass/charge (m/z) values and intensities produced by high-resolution tandem MS.
## Features
- Generates cyclic peptides using given mass spectra.
- Scores candidate peptides against experimental spectra.
- Filters candidates based on score.
---
## Requirements
Make sure you have the following Python packages installed:
```bash
Itertool
collections
```
## License


[MIT](https://choosealicense.com/licenses/mit/)
