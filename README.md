# 2022 IPUMS Census Analysis

## Overview

This repo analyzes the 2022 ACS census dataset provided by IPUMS.


## File Structure

The repo is structured as:

-   `data/raw_data` contains the raw data as obtained from the IPUMS website.
-   `data/analysis_data` contains the cleaned dataset that was constructed.
-   `model` contains fitted models. 
-   `other` contains relevant literature, details about LLM chat interactions, and sketches.
-   `paper` contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper. 
-   `scripts` contains the R scripts used to simulate, download and clean data.


## Statement on LLM usage

Aspects of the code were written with the help of ChatGPT 4o. Usage is included
in other/llm/usage.txt

## Some checks

- [ ] Change the README title 
- [ ] Remove files that you're not using
- [ ] Update comments in R scripts
- [ ] Remove this checklist