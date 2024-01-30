# Coronavirus-DrugDiscovery


# SARS Coronavirus 3C-like Proteinase Inhibitor Analysis

## Project Overview
This project involves the analysis of bioactivity data for potential inhibitors of the SARS coronavirus 3C-like proteinase. It includes computational assessment of molecular descriptors, bioactivity class distributions, and statistical evaluations to identify promising compounds for further drug development efforts.

## Dataset
The dataset includes compounds tested for activity against the SARS coronavirus 3C-like proteinase, with data points such as IC50 values, molecular weight (MW), partition coefficient (LogP), and the number of hydrogen donors and acceptors.

## Analysis Workflow
- Data preprocessing and cleaning.
- Visualization of molecular descriptor distributions across bioactivity classes (active vs. inactive).
- Statistical testing (Mann-Whitney U Test) to determine significant differences between the bioactivity classes.

## Key Findings
- pIC50 values are a significant discriminator of bioactivity, with active compounds exhibiting higher potency.
- Active compounds tend to have a lower molecular weight.
- The number of hydrogen acceptors is significantly different between active and inactive compounds, suggesting its importance in bioactivity.
- Lipophilicity (LogP) does not show a significant difference between active and inactive compounds within this dataset.

## Repository Contents
- `bioactivity_data.csv`: Preprocessed bioactivity data used in the analysis.
- `bioactivity_preprocessed_data.csv`: Data after classification based on bioactivity.
- `data_analysis.ipynb`: Jupyter notebook containing the analysis code.
- `plot_*.pdf`: Visualization plots of the molecular descriptors.
- `mannwhitneyu_*.csv`: Results from the statistical tests.

## Dependencies
- Python 3.8+
- Pandas
- NumPy
- RDKit
- Matplotlib
- Seaborn
- SciPy

## Usage
The Jupyter notebook `data_analysis.ipynb` contains all the analysis steps and can be run cell by cell to reproduce the findings.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License
[MIT License](LICENSE)

## Contact
For any queries or assistance, please open an issue in the repository, and I will get back to you.

## Acknowledgements
This project was conducted as part of the research work on coronavirus inhibitors. I would like to thank all contributors and data providers for making this analysis possible.

