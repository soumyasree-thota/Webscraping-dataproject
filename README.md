# Webscraping-dataproject
# Multi-Source Web Data Extraction & Structuring Pipeline
##VIDEO WALKTHROUGH
PART1:https://www.loom.com/share/860f67a3751748f6aabd29cc7e844e10
PART2:https://www.loom.com/share/35130f9aad904f9ba3e656fee013a770
## Overview
This project was developed during my internship and focuses on extracting and structuring data from multiple law firm websites with varying layouts and formats.
The objective was to automate the process of collecting semi-structured web data and convert it into a consistent, analysis-ready dataset that can be used for reporting and decision-making.

## Key Objectives
- Automate data collection from multiple external sources
- Handle variability in website structures and layouts
- Standardize extracted data into a unified schema
- Deliver clean, structured datasets for downstream analytics

## Technologies Used
- **Python**
- **Playwright** 
- **BeautifulSoup** 
- **Pandas** 


## Project Workflow
1. **Data Source Identification**
   - Targeted multiple law firm websites with professional profile data

2. **Data Extraction**
   - Used Playwright to handle dynamic content and page navigation
   - Extracted profile URLs via sitemap or pagination
   - Scraped individual profile pages

3. **Data Parsing**
   - Parsed HTML content using BeautifulSoup
   - Extracted fields such as:
     - Name (First, Middle, Last)
     - Job Title
     - Email and Phone
     - Location
     - Education (Law & Undergraduate)
     - Bar Admissions
     - Languages
     - Practice Areas

4. **Data Cleaning & Transformation**
   - Standardized text fields
   - Handled missing or inconsistent values
   - Created helper functions for parsing complex fields (e.g., names, education)

5. **Data Structuring**
   - Organized extracted data into a consistent schema across all sources
   - Ensured uniform column structure for all datasets

6. **Data Output**
   - Exported cleaned datasets into Excel format using Pandas
   - Enabled easy usage for reporting and further analysis

## Output
The final output consists of structured datasets where:
- Each row represents an individual profile
- Each column represents a standardized attribute
Example fields include:
- Name
- Job Title
- Email
- Location
- Education
- Bar Admissions
- Languages
- Profile URL
- 
## Challenges & Solutions
Challenge:
Different websites had different HTML structures and layouts.

Solution:
- Implemented customized scraping logic for each website
- Adapted selectors and parsing methods per source
- Used flexible helper functions to handle inconsistencies

## Business Value
This project demonstrates how semi-structured web data can be transformed into structured datasets.
It enables:
- Reduced manual data collection effort
- Improved data consistency and quality
- Faster access to data for analytics and reporting

## Future Improvements
- Integrate into a fully automated pipeline with scheduling
- Add data validation and quality checks
- Build dashboards for visualization (Tableau/Power BI)

## Author
Soumya Sree Thota  
 
