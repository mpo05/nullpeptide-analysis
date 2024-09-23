
# Pathogenic Nullpeptide Analysis

This repository contains a Jupyter Notebook that focuses on analyzing DMS (Deep Mutational Scanning) samples. The main hypothesis was that peptides that occur after mutations (nullpeptides) are associated with pathogenic states. The notebook processes various datasets and performs multiple analyses, including data manipulation, identification of enriched nullpeptides, visualization, network analysis and identification of nullpeptide families.

## Project Overview

The purpose of this notebook is to handle and analyze DMS samples with a focus on human-related mutations (substitutions and indels). Key tasks include:

- Loading DMS substitution and indel data.
- Filtering human DMS samples.
- Creating directories and organizing datasets.
- Performimg data manipulation and DMS score scaling
- Using Fisher's exact test to detect enriched nullpeptides
- Visualizing data trends using matplotlib and seaborn.
- Conducting network analysis using NetworkX, to identify nullpeptide families.

## Files Included

- **`nullpeptides_DMS_samples.ipynb`**: The main notebook file for performing the data analysis.

## Required Libraries

The notebook requires several Python libraries to function properly. Make sure to install the following dependencies:

- `os` and `shutil`: For handling file paths and copying files.
- `numpy` and `pandas`: For data manipulation and handling large datasets.
- `ahocorasick`: For efficient string matching.
- `tqdm`: For progress tracking.
- `matplotlib` and `seaborn`: For data visualization.
- `scipy`: For statistical analysis.
- `networkx`: For network analysis of adjacency matrices.

You can install these packages via pip:

```bash
pip install numpy pandas ahocorasick tqdm matplotlib seaborn scipy networkx
```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/mpo05/nullpeptides-analysis.git
   ```
2. Install the required dependencies.
3. Open the notebook using Jupyter:
   ```bash
   jupyter notebook nullpeptides_DMS_samples.ipynb
   ```
4. Run the cells in the notebook to reproduce the analysis.

## Output

- Visualizations of data trends are saved in specified output directories.
- Network analysis results are stored as graphs in the respective directories.

## License

This project is licensed under the MIT License.
