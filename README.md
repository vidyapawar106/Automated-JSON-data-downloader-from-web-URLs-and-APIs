# Web Scraping/Automated JSON data downloader
This project aims at automating the process of downloading/writing JSON data from web URLs/APIs into Google Sheets and CSV files. Follow these steps to set up your Google accounts and download the required Credentials.

# Step 1: Setting up Google Sheets API
Log in with Techworks Marine Gmail account on GCP console to enable the Google Sheets API: https://support.google.com/googleapi/answer/6158841?hl=en  
Download the API Key in Json format from the account where the code and other packages are located.

# Step 2: Create a Blank Google Sheet
Create a new Google Sheet with Satellite Overpasses name and copy the Sheet ID from the URL.
Edit the viewing/editing permissions.

# Step 3: Create a webhook on Teams
A part of code sends the data on Teams group channel as well. Therefore, to send the messages to teams we need to create a webhook in Teams using https://docs.microsoft.com/en-us/microsoftteams/platform/webhooks-and-connectors/how-to/add-incoming-webhook
