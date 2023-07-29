# Medication-Info_fromOpenFDA
Personal_Project
--
## Project Overview
This project aims to create a webpage called that displays a list of medication and provides a user-friendly webpage with options to choose between Over the counter or Prescription or Discontinued medication type and view results with seamless experience for users.

## Data Sources 

FDA Drugs API to access information about medications marketing status and label information. This data will help provide accurate and up-to-date information about each medication
- [FDA Drugs API](https://api.fda.gov/drug/drugsfda.json)

## Technical Implementation
* Mongo DB
* Python Flask API
* Vue.js, Plotly.js
* BootsrapVue
* HTML

## UI Elements 
* Option Button to choose medication type
* Table that display Medication name, dosage form, Intake route and active Ingredients/strength
* Filter and sort the displayed records
* Pie-Chart view that displays medication count by dosage form
* Bar-Chart view that displays medication count by Intake route

## Additional UI Features
* Data from source (FDA site) will be refreshed at page load(Drugs@FDA API call using Marketing staus).
* Optionally, a button "Refresh data again? Click Me" is also provided to refresh data from source(Drugs@FDA API call using Marketing staus).
* Dashboard will display with more detailed infomration directly from FDA website using Drug Labeling API call using Medication brand name when the user clicks on specifc medications "More Details" button.
