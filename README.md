---
output:
  pdf_document: default
  html_document: default
---
# SBurchFinalProject2020
CH4 levels, agriculture, SDG/NDC Commitments

# <SBurchFinalProject2020>
***Still a work in progress this week! I need to play around with the datasets some more this week to see if I can narrow the scope a bit further. This will help me, especially in regards to formalizing the metadata section for this assignment. I'll be sure to update you all of these changes, and please let me know if you have any specific suggestions.***

## Summary

The purpose of this repository is to gain a better understanding of global CH4 (methane) emissions and if and what nations are doing to reduce such emissions within their agricultural sector. Why is this important and relevant? According to FCRN, "...global methane emissions are today adding heat to what is already a dangerously warming climate, a warming largely but not exclusively caused by the growth in fossil fuel use and by (partly livestock-induced) forest clearance. The context has changed, and the importance of animal related methane emissions has increased." More specifically, the objective of this analysis is to learn which nations emit the highest amount of CH4 within their agricultural sector and if those respective nations have made Nationally Determined Contributions (NDC) and Sustainable Development Goals (SDG) commitments to reduce their agriculturally-associated CH4 emissions. The following research questions will be addressed: 

1. Using the most recent data (years 2013-2017), which nations have emitted the highest rates of CH4 within their respective agricultural sector? The research will be wrangled to assess the top 20 highest emitter nations.

2. Which of those countries have made NDC and SDG commitments to reduce their agricultural sector CH4 emissions? Are those committments specific to reducing CH4 emissions from animal agricultural production?

## Investigators

Name: Samantha Burch
Affiliation: Duke University
Contact info: samantha.burch@duke.edu
Role: Master of Environmental Management Candidate

## Keywords

CH4; methane; agriculture; GHG emissions; emissions; ruminant; enteric fermentation; NDC; SDG

## Database Information

All data was accessed in April 2020 and has been downloaded from the following three sources: 

1) FAOSTAT on Food and Agriculture Organization of the United Nations, which "provides free access to food and agriculture data for over 245 countries and territories and covers all FAO regional groupings from 1961 to the most recent year available."

Additional information regarding the dataset: "Greenhouse gas (GHG) emissions from enteric fermentation consist of methane gas produced in digestive systems of ruminants and to a lesser extent of non-ruminants. The FAOSTAT emissions database is computed following Tier 1 IPCC 2006 Guidelines for National GHG Inventories vol. 4, ch. 10 and 11 (http://www.ipcc-nggip.iges.or.jp/public/2006gl/vol4.html)."

Please note that the "FAOSTAT Emissions data are estimated by FAO and may not coincide with GHG data reported by member countries to UNFCCC. The database is intended primarily as a service to help member countries assess and report their emissions, as well as a useful international reference."

2) FAO's Sustainable Development Goals (SDG) Data Portal, providing key information to support countries in tracking progress toward SDGs.

3) The Climate Watch Data Explorer, which provides information on NDC-SDG linkages across countries and their agricultural sectors.

## Folder structure, file formats, and naming conventions 

#Folder Structure
The following folders are contained in the repository and include the following files within: 

1. Data/Raw: This folder contains the original raw data as a csv file.
2. Data/Processed: This folder contains the processed data as a csv file.
3. Code: This folder contains all code from R Script.
4. Output: This folder includes obvious descriptions.

#File Formats
The formats of all data files for the various purposes contained in the repository are included in a csv file format.

#Naming Conventions
My file names follow the following naming convention:
**databasename** : refers to the database where data originated
**datatype** : description of the data
**details** : additional descriptive details (these are specifcally key for the processed data)
**stage** : refers to the stage in data management pipelines (whether something falls under 'raw,' 'cleaned,' or 'processed)
**format**: non-propietary file format such as csv or text

## Metadata
***will be refined as my project develops this week.***

Column Name      | Column Notes
---------------- | -------------
Country          | Includes a list of all of the world's countries 
Data Source      | CAIT database
Sector           | Agriculture
Gas              | CH4
Unit             | MtCO‚ÇÇe
Years ('11-'16)  | Total amount of MtCO‚ÇÇe emitted
SDG              | Specifies which of the 17 SDGs the country has committed to
SDG Targets      | Specifies SDG-specific targets               
NDC              | Specifies NDC country commitments

## Scripts and code

***this will be updated as I refine my project further over the coming week.***

Please find below a list software scripts/code contained in the repository and a description of their purpose:

The file named 'Data Wrangling' was used to process the 'raw data' to 'processed data.'

## Quality assurance/quality control

At this moment, there are no relevant QA/QC procedures to be taken with the data. 