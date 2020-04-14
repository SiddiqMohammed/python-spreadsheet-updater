# Python Spreadsheet updater
Using the google spreadsheets API, gspread library, and pyqt5, I've made a simple spreadsheet updater.

A dialog box opens up and asks the user for the data that is supposed to be updated in the spreadsheet online. When the user writes the data and submits, the spreadsheet is updated automatically.
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the libraries.

```bash
pip install gspread 
pip install pyqt5 
```

## Usage

```python
from oauth2client.service_account import ServiceAccountCredentials
from pprint import pprint
```
1. Set up to get the API access. To gain the access, go to the "google cloud platform" and create a new project and install and enable the "google drive" & "spreadsheet" which can be found in the library section. 

2. Get the JSON file from your API. This JSON file contains all your credentials that allow the API to connect and interact with your code. I named my JSON file "creds"

3. Create a new spreadsheet and name it and share it with the "client-ID" email that you receive in the JSON file from the API

If you want to create a GUI with custom dialog boxes then I suggest you to learn to use pyqt5. It is a great tool that is in my opinion much better than the alternatives that I've come across.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
