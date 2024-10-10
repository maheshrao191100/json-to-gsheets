# json-to-gsheets
Scrap JSON data (webpage) to Google Sheets (GCP Service Account) or to CSV file

1. These steps extract data (XML) from a webpage.
2. Extract static data is much simpler using XML (=IMPORT XML)
3. Not all web pages store tables in static format, some are dynamic.
4. Dynamic table usually stores data in JSON format.

5. Open the target web page on a browser.
6. Go into inspect pane.
7. Select 'Network' from menu bar
8. Refresh the webpage
9. Find for Type 'fetch'
10. Check the URL which contain JSON format text
