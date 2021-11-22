# Pollstar Bands: A Regression Analysis
A regression analysis I did for the Emporia Granada Theatre (EGT) to help predict the efficacy of most any band we may consider hiring in the future.

# Summary

Predictor variables were selected from Pollstar and Facebook and regressed onto Income, Profit, and Bar Sales for the Emporia Granada Theatre in order to help answer the question "Which bands should we hire in the future to maximize profits?".  Ultimately, a very useful model for predicting Income was produced (With a predictive R^2 value of 62%), and the best models for each regressor were programmed into a user dashboard on Google Sheets:
https://docs.google.com/spreadsheets/d/1Sc3ehiAH667C-rpUyheu4uyhFGBcUWJx0gSsMmAyJGA

This gives the EGT insight into unfamiliar bands, and allows a booking agent with limited experience to make more informed decisions. Armed with these powerful insights, booking has yeilded higher profit margins while mitigating risks associated with hiring costly bands.

# Files
1. README.md - This file
2. Pollstar Regression Report.pdf - An extensive report in PDF format outlining the methods used and the overall procedure of the analysis.  Anyone curious about the methods used in this analysis should be directed to this file.
3. Pollstar Regression Dashboard.xlsx - Dashboard for utilizing the resultant models, in the form of a downloadable Excel workbook. Anyone interested in the end-result may download this file or simply view the original here:
https://docs.google.com/spreadsheets/d/1Sc3ehiAH667C-rpUyheu4uyhFGBcUWJx0gSsMmAyJGA

Since the dashboard was built in Google Sheets, that may be the best place to view it.  Proper formatting is not guaranteed in MS Excel. At EGT the dashboard is hosted on Google Sheets and is connected to a Google Form to make adding new bands easy and user-friendly.

Usage of the dashboard is simple: You simply select a band from the dropdown list at the top of the dashboard, and the information will auto-populate.  New bands can be added in the Bands sheet.  If a band is selected that does not meet the requirements of a given model, this will be indicated by a cell highlighted in red, specific to whatever range assumption is being violated.

# Disclaimer
The raw data used in this analysis includes specific financial records and has therefore been omitted to protect the privacy of the Emporia Granada Theatre.


