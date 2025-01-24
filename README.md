# website-downloader-project
//Python Code for the Command-Line Tool
Use the requests module to fetch the HTML content.
Use BeautifulSoup from bs4 to parse and find links to other pages, images, and JavaScript files.
Use os and shutil for managing file storage locally.
Implement a recursive function that respects the crawl depth.
Use a queue system to manage URLs to be visited.
//Usage:
Install Dependencies: You'll need requests and BeautifulSoup4 installed:
bash
pip install requests beautifulsoup4
Run the Script: To use this script, you would run it from the command line as follows:
python download_website.py https://example.com 2
This command will download the website at https://example.com up to a depth of 2.

//Running the Code in Google Colab / Jupyter Notebook:
Open Google Colab or Jupyter Notebook:
If you're using Google Colab, go to Google Colab and start a new notebook.
If you're using Jupyter Notebook, open your local Jupyter environment.
Install Required Libraries: Before running the script, you need to install the required libraries: requests and beautifulsoup4. In a cell, run the following command:
!pip install requests beautifulsoup4

