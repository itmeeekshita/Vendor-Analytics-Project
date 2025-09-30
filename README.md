# Vendor Analytics Project

## Overview
The Vendor Analytics Project is a data analytics solution designed to process and analyze large vendor datasets, including sales and purchase information. The project leverages Python for data handling, Git LFS for managing large CSV files, and visualization tools for generating meaningful insights. This repository contains raw CSV data files, Python scripts, and analysis notebooks to demonstrate data processing, transformation, and analytics workflows.

## Features
- Handles large CSV datasets efficiently using Git Large File Storage (LFS).
- Processes sales and purchase data for vendors.
- Supports data cleaning, aggregation, and analysis workflows.
- Generates visual insights using Python visualization libraries.
- Easily extensible for additional data sources or analytics tasks.

## Repository Structure
vendor-analytics-project/
├─ data/                  # Raw CSV data (tracked with Git LFS)
│  ├─ purchases.csv
│  └─ sales.csv
├─ scripts/               # Python scripts for data processing
├─ notebooks/             # Jupyter notebooks for analysis
├─ .gitattributes         # Git LFS tracking configuration
└─ README.md

## Getting Started
### Prerequisites
- Python 3.8+  
- Git & Git LFS installed  
- Jupyter Notebook or any Python IDE (optional, for notebooks)

### Installation
1. Clone the repository:
git clone https://github.com/itmeeekshita/Vendor-Analytics-Project.git
cd Vendor-Analytics-Project

2. Install dependencies:
pip install -r requirements.txt

Note: Large CSV files are tracked with Git LFS. Make sure Git LFS is installed and initialized:
git lfs install
git lfs pull

### Usage
- Run Python scripts from the scripts/ folder:
python scripts/your_script.py
- Open and explore Jupyter notebooks in the notebooks/ folder for data analysis and visualization.

## Contributing
Contributions are welcome! You can add new data processing scripts, improve data visualization, or extend analytics capabilities.

## License
This project is open-source and available under the MIT License.

## Notes
- Large CSV files (purchases.csv and sales.csv) are tracked with Git LFS due to size (>100MB).  
- Ensure Git LFS is installed before cloning or pulling to avoid errors.

## Contact
For any questions or issues, please contact Eekshitha Singamsetty.
