# SAT XML Data Extraction and Concept Combination (tools-sat_xml_merge)

## Project Overview
This project aims to develop a system capable of extracting relevant data from SAT (Sistema de Administración Tributaria) XML files and combining related concepts into a structured CSV format. The consolidated data will be a valuable resource for analysis, reporting, and decision-making within the organization.

## Key Features
Efficient XML Parsing: Extracts key data elements from SAT XML files.
Concept Combination: Identifies and combines related concepts into a structured format.
Data Cleaning and Validation: Ensures data quality and integrity.
Scalability: Handles large volumes of XML data.

## Installation
### Prerequisites:
- Python (version 3.6 or later)
- Required libraries:
  - Basic python libs (loggin, os, pathlib, sys, xml, csv, sys)

### Installation Steps:
1. Clone this repository:
> `git clone https://github.com/silver1592/tools-sat_xml_merge.git`

2. Install dependencies:
> `pip install -r requirements.txt`

## Usage
Prepare XML Files: Place your SAT XML files in the data directory.
Run the Extraction and Combination Script:

> `python main.py`

Output: The combined data will be saved as a CSV file in the output directory.


Customization
Configuration: Modify the configuration file (config.yaml) to customize extraction rules, concept combination logic, and output format.
Data Cleaning: Adjust data cleaning procedures as needed to address specific data quality issues.