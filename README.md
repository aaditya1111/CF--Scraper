# CF--Scraper

Downloads Contest problems and tutorials

The scraper does the following:

1): Makes a Problem Set folder.

2): Requests for the range of contest IDs the user wants to download.

3): Maintains a text file which tracks whether the requested contest has already been downloaded.

4): Creates separate folders for each valid contest and downloads all the problems and tutorials as PDFs. Note that some Codeforces contests don't have tutorials.

Run by executing runner.py It is a Python3 file

Requirements: Python3; Python libraries: bs4, requests, pdfkit, lxml; Application: wkhtmltopdf

Terminal commands for requirement installation in Ubuntu:
  sudo pip3 install bs4
  sudo pip3 install requests
  sudo pip3 install lxml
  sudo pip3 install pdfkit
  sudo apt-get install wkhtmltopdf
  
Created by Aaditya Kumar Rai
