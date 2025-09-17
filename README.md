# Kendal Tree Map

Data is maintained in this Google spreadsheet:
https://docs.google.com/spreadsheets/d/1ovxGnuXLpHrAXRyCrsLlLKveg9bxAjgbkO-5WOyf4I0/edit?usp=sharing

Note that there are two QGIS projects in the `qgis` folder.

`kendal-trees-from-google-sheets.gqz` attempts to load the live data directly from the Google sheet.  This works in the latest QGIS versions (3.44) on Windows, but may not work on Mac.

If that doesn't work for you, then use the `kendal-trees-from-local-csv.qgz` project, which will load the data from the .csv file, which was simply exported from Google sheets and saved to the `qgis` folder.  To update to the latest version of the data from the Google spreadsheet, go to the URL above, then go to the "File" menu > Download > Comma Separated Values (.csv) and save the file into the `qgis` folder, overwriting the existing file.  Then open the `kendal-trees-from-local-csv.qgz` project file.