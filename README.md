# jj-av-dallas
This is the R repository for the Arnold Ventures Dallas County Juvenile Justice Probation Conditions Project

## Project Purpose
The CSG Justice Center is partnering with sites to assess and improve their approach to juvenile probation condition setting and enforcement, following the principles laid out in the Breaking the Rules Toolkit. CSG Justice Center staff will assess the use of graduated responses, technical violations, and revocations, including type, frequency, who is receiving them, why, and the outcomes. Case-level data analysis will describe the population of youth on probation, including use of technical violations and reasons for violations.

## Assigned Research Staff
Becky Cohen, Emily Rogers (for analysis), and Andrew Byrum (for data cleaning and analytic file prep)

## Teams/SharePoint Project Folder
Sharepoint path to JC Resarch folder for JJ AV Dallas Project: https://csgorg.sharepoint.com/:f:/s/Team-JC-Research-JJ_AV/EuGqNP2adN9LpUy7_EShBQIBzTA9ZNIK6YxZY9R7GWXsrg?e=LfOizE

## Netlify Site
Here's the path to the Netlify-hosted site, which will be updated with data diagrams, codebooks, and code for analytic file creation throughout the project: https://jj-av-dallas-county.netlify.app/

The password is csgjc_dallas

## Repository Structure

```
│   ├── _freeze/ # folder with frozen copies of entire repo; using 'auto' freeze option to "denote that documents only be re-rendered when their source file change"
│   ├── _site/ # folder with knitted html files that is hosted by netlify site
|   |    ├── data_cleaning/ # copy for site
|   |    ├── data_diagram/ # copy for site
|   |    ├── img/ # folder with files/packages for respective html (b/c rmd is not self contained)
│   │    |   ├── csg-logo.png
│   │    |   ├── favicon.png
│   │    |   ├── jj_av_dallas_data_diagram.png
|   |    ├── jj_av_dallas_data_codebooks_file/figure-html/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── site_libs/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── index.html/ # knitted landing page html for site
|   |    ├── jj_av_dallas_create_analytic_files.html/ # knitted html for site
|   |    ├── jj_av_dallas_create_analytic_files.html/ # knitted html for site
|   |    ├── jj_av_dallas_data_codebooks.html/ # knitted html for site
|   |    ├── jj_av_dallas_data_diagram.html/ # knitted html for site
|   |    ├── jj_av_dallas_data_diagram_viz.html/ # knitted html for site
|   |    ├── jj_av_dallas_questions_updates.html/ # knitted html for site
|   |    ├── jj_av_dallas_preliminary_descriptives.html/ # knitted html for site
|   |    ├── search.json
|   |    ├── style.css
│   ├── data_cleaning/
│   │    |   ├──  jj_av_dallas_exploration_import_clean.Rmd/ # initial cleaning file for import and basic data prep
│   ├── data_diagram/
│   │    |   ├──  jj_av_dallas_data_diagram_build.qmd/ # file to create data diagram for project
│   ├── img/           
│   │    |   ├── csg-logo.png
│   │    |   ├── favicon.png
│   │    |   ├── jj_av_dallas_data_diagram.png
|
├── index.qmd/ # landing page to knit for site
├── jj_av_dallas_create_analytic_files.qmd/ # html to knit for site; file builds both analytic files -- pushing to site for QA with team
├── jj_av_dallas_data_codebooks.qmd/ # html to knit for site -- creates codebooks for each file
├── jj_av_dallas_data_diagram_viz.qmd/ # html to knit for site -- renders data diagram
├── jj_av_dallas_questions_updates.qmd/ # html to knit for site -- running list of questions and communication with Dallas County
├── jj_av_dallas_preliminary_descriptives.qmd/ # html to knit for site -- basic descriptives for files and variables of interest
├── .gitignore
├── .nojekyll
├── README.md
├── _quarto.yml/ # site structure
└── theme.css
```

