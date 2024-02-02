# Low Energy Nuclear Reaction Research Paper Download
This Python script automates bulk research paper downloading for my machine-learning research.

## 🤖 Overview

The script extracts paper titles and downloads links from conferences like NeurIPS and ICML. It then downloads the PDFs for analysis.

Key features:

- Scrapes conference websites for links 
- Exports paper metadata to Excel
- Downloads PDFs in bulk
- Easy configuration - update target URL

## 🚀 Getting Started

### Requirements

Python 3+ 

Python libraries:

- Requests
- BeautifulSoup 
- Pandas
- OS

### Usage

1. Update `url` variable to target conference website 
2. Run ipynb file
3. Find downloaded papers in `/data` directory
4. Metadata exported to `research_metadata.xlsx`

## 📈 Results

The script outputs:

- `research_metadata.xlsx` - Excel file with paper titles and download links
- Downloaded PDF papers in `/data` directory 

## 📜 Disclaimer 

This code is for educational/research purposes only. Please check website terms of use before bulk downloading and please obtain necessary permissions before scraping any website.
