# jj-av-dallas
This is the R repository for the Arnold Ventures Dallas County Juvenile Justice Probation Conditions Project

## Project Purpose
The CSG Justice Center is partnering with sites to assess and improve their approach to juvenile probation condition setting and enforcement, following the principles laid out in the Breaking the Rules Toolkit. CSG Justice Center staff will assess the use of graduated responses, technical violations, and revocations, including type, frequency, who is receiving them, why, and the outcomes. Case-level data analysis will describe the population of youth on probation, including use of technical violations and reasons for violations.

## Assigned Research Staff
Becky Cohen, Emily Rogers (for analysis), and Andrew Byrum (for data cleaning and analytic file prep)

## Teams/SharePoint Project Folder
Sharepoint path to JC Resarch folder for JJ AV Dallas Project: https://csgorg.sharepoint.com/:f:/s/Team-JC-Research-JJ_AV/EuGqNP2adN9LpUy7_EShBQIBzTA9ZNIK6YxZY9R7GWXsrg?e=LfOizE

## Databook Site (with Netlify)
Here's the path to the Netlify-hosted site, which will be updated with data diagrams, codebooks, and code for analytic file creation throughout the project: https://jj-av-dallas-county.netlify.app/

The password is csgjc_dallas

## Repository Structure

```
│   ├── _freeze/
|   |    ├── img/
│   │    |   ├── csg-logo.png
│   │    |   ├── favicon.png
│   │    |   ├── iowa_revocation_data_mapping.png
|   |    ├── iowa_appointment_contact_trend_analysis_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── iowa_data_diagram_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── iowa_district_descriptives_analysis_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── iowa_revocation_count_trend_analysis_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── iowa_revocation_rate_trend_analysis_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── iowa_study_sample_analysis_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── search.json
|   |    ├── theme.css
│   ├── _site/
|   |    ├── img/
│   │    |   ├── csg-logo.png
│   │    |   ├── favicon.png
│   │    |   ├── iowa_revocation_data_mapping.png
|   |    ├── iowa_appointment_contact_trend_analysis_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── iowa_data_diagram_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── iowa_district_descriptives_analysis_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── iowa_revocation_count_trend_analysis_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── iowa_revocation_rate_trend_analysis_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── iowa_study_sample_analysis_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── search.json
|   |    ├── theme.css
│   ├── data_cleaning/
│   │    |   ├──  research/ # folder for all research-specific cleaning (for final presentation)
│   │    |   |   |   ├── district_level_analytic/ # file aggregated by district for research
│   │    |   |   |   |   ├── 1_greg_request_district_level_pre_mid_post_covid.Rmd # produce counts of cases and violations due to violent offenses
│   │    |   ├──  updated_data_pull_through_12_2021/ # folder for cleaning updated IDOC data pull (6/2021 through 12/2021)
│   │    |   |   ├── 1_iowa_preliminary_exploration_import_clean.Rmd # initial cleaning file to import, join, and clean important analytic variables w/ updated data
│   │    |   |   ├── 2_iowa_cleaning_trend_analysis.Rmd # second cleaning step, produces several analytic files for data analysis & combines original and new data
│   │    |   ├──  1_iowa_preliminary_exploration_import_clean.Rmd # initial cleaning file to import, join, and clean important analytic variables
│   │    |   ├──  2_iowa_cleaning_trend_analysis.Rmd # second cleaning step, produces several analytic files for data analysis syntax/Rmd's
│   │    |   ├──  iowa_violation_cleaning.Rmd # intial cleaning file to prep violation data for analytic prep in '2_iowa_cleaning_trend_analysis'
│   ├── data_diagram/
│   │    |   |   ├── img/
│   │    |   |   |   |   ├── iowa_revocation_data_mapping.png/ # data diagram output
│   │    |   |   ├── iowa_data_diagram_files/ # folder with files/packages for respective html (b/c rmd is not self contained)
│   │    |   ├──  iowa_data_diagram.Rmd 
│   │    |   ├──  iowa_data_diagram.html
│   │    |   ├──  iowa_revocation_data_mapping.Rmd 
│   │    |   ├──  iowa_revocation_data_mapping.html
│   ├── img/           
│   │    |   ├── csg-logo.png
│   │    |   ├── favicon.png
|
├── .gitignore
├── .nojekyll
├── README.md
├── _site.yml
├── index.Rmd
└── theme.css
```

