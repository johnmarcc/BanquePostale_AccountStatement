# Project Title
BanquePostale_AccountStatement

## Getting Started

__For test only__

Python script to download Bank account statements automatically from labanquepostale.fr with a firefox instance in Headless mode (script running in background) or in foreground (script opens a firefox window on the platform)

This script uses OpenCV librairy to detect which image buttons to click on the virtual keyboard displayed in the html Login page according to 
password

## Input JSON file
All the input parameters (bank account number, password...) are extracted from a JSON file "BanquePostale_Account.json" that must be set in the directory the script is launched

__1- param_NumeroDeCompte: Bank account 11 char (eg '123456789X0')
__2- param_ID: id to connect to internet site, 6 digits
__3- param_PWD: password to connect to internet site, 6 digits
__4- param_DownloadFolder: local download directory where the pdf bank account statements are downloaded
__5- param_HEADLESS_PROCESS: 'True' when we want the script to get a firefox instance in a background process else 'False' for the foreground process

## Output PDF file
At the end od the script, the bank account statement file PDF is downloaded to the specified directory

## Authors

https://github.com/johnmarcc
