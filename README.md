# IsoPairFinder_DemoData_DiffTools

This repository provides demo data and results to demonstrate the use of different metabolomics data processing pipelines (e.g., MSDIAL, MZmine, XCMS) using the IsoPairFinder workflow. The data is organized to facilitate benchmarking, reproducibility, and method development for isotope labeling experiments.

## Repository Structure

- `00_raw_data/`: Raw instrument data files, organized by experiment and sample. The raw LC-MS data is acquired from Agilent 6545XT QTOF instruments and includes both C12 and C13 isotopologues.
- `00_mzML/`: Converted mzML files for each sample, grouped by experiment.
- `01_input_data_IsoPairFinder/`: Input data for IsoPairFinder, including peak tables and sample information, which are exported and formatted from different tools (MSDIAL, MZmine, XCMS).
- `02_exported_data/`: Example output results from IsoPairFinder for each tool.

## Data Organization

- Each tool (MSDIAL, MZmine, XCMS) has its own subfolder containing:
  - Peak tables for C12 and C13 isotopologues.
  - Sample information files.
  - mzML files for each sample group (e.g., hyuA_12C, hyuA_13C, WT_12C, WT_13C, ms2).
- Exported results are provided as zipped files for demonstration.

## Usage

1. Use the provided mzML and peak table files as input for IsoPairFinder or other analysis tools.
2. Demonstrate the results across different data processing pipelines using the exported results.
3. Use the raw data for reprocessing or method development.

## Contact

For questions or feedback, please contact:

**Zhiwei Zhou**  
Department of Pathology, Stanford University  
Email: zhouzw@stanford.edu

## Citation

If you use this repository or data in your work, please cite the relevant IsoPairFinder publication and acknowledge the data source.

- Zhiwei Zhou, Dylan Dodd*, et al. **IsoPairFinder: An R package for identifying potential intermediates from Stable Isotope Tracing metabolomics data**, *In preparation*, 2025.


## License
<a rel="license" href="https://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a> 
This work is licensed under the Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)
