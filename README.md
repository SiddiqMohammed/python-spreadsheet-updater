# python-spreadsheet-updater
Update Google Spreadsheets using inputs from Python

DESCRIPTION:

Using the google spreadsheets API, gspread library, and pyqt5, I've made a simple spreadsheet updater.

A dialog box opens up and asks the user for the data that is supposed to be updated in the spreadsheet online. When the user writes the data and submits, the spreadsheet is updated automattically. 

INSTALLATION:

In order for one to run this, you'll first need to install a few things

1. PyQt5
2. PyQt5-tools

OTHER REQUIREMENTS:

Apart from the above mentioned libraries, you'll also need to have the API access. To gain the access, go to the "google cloud platform" and create a new project and install and enable the "google drive" & "spreadsheet" which can be found in the library section.

Get the json file from your API. This json file contains all your credentials that allow the API to connect and interact with your code. [pls don't be dumb like I was when I first started out and shared the credentials 🤦‍♀️]. I named my json file "creds"

Create a new spreadsheet and name it and share it with the "client-ID" email that you recieve in the json file from the API



If you want to create custom dialog boxes then I suggest you to learn to use pyqt5. It is a great tool that is in my opinion much better than the alternatives that I've come across.

LINKS TO HELP WITH REPLICATION OR INSTALLATION:

Watch this for pyqt5 tutorial - https://www.youtube.com/watch?v=ksW59gYEl6Q
watch this for setting up API & integrating python with spreadsheets - https://www.youtube.com/watch?v=cnPlKLEGR7E
