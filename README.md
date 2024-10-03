# 2022 IPUMS Census Analysis

## Overview

This repository analyzes data from IPUMS USA. To obtain the data, follow these steps:

1. Google "IPUMS USA" and go to the first link: https://usa.ipums.org/usa/. 
2. Click "Get Data" on the home screen.
3. Click "Select Samples". In USA Samples, tick the box that says "Default sample from each year", and then tick the box next to 2022 ACS. This should the only box ticked. Afterwards, click "submit sample selection".
4. Under Select Harmonized Variables, click the Household drop down menu and select Geographic. Click the + under "Add to cart" next to variable `STATEICP`.
5. Do the same for variable `SEX` in Demographic under the Person menu, and for variable `EDUC` in Education under the Person menu.
6. Click "View Cart". You should be taken to the extract request, with 1 sample and 14 variables. Change the data format to .csv, and then press "Submit Extract". 
7. If you are not logged in to an account, you will be prompted to log in, or create an account. Once you are finished this, you can view and download the csv extract. There is also a link to the codebook that explains the variables in the dataset.

## Statement on LLM usage

Aspects of the code were written with the help of ChatGPT 4o. Usage is included
in other/llm/usage.txt
