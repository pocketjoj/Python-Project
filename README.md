# An Analysis of Medicare 2017 Surgical Claim Data
## Code Louisville Data Analysis Project

Thank you for your interest in my data analysis project! In this project, I will be using a Jupyter Notebook to analyze data furnished by a CMS (Medicare) API.

CMS API Endpoint, 2015: https://data.cms.gov/resource/uqfq-w9cg.json
CMS API Endpoint, 2016: https://data.cms.gov/resource/jtra-d83c.json
CMS API Endpoint, 2017: https://data.cms.gov/resource/2zuc-y5mm.json
API Documentation, 2015: https://dev.socrata.com/foundry/data.cms.gov/uqfq-w9cg
API Documentation, 2016: https://dev.socrata.com/foundry/data.cms.gov/jtra-d83c
API Documentation, 2017: https://dev.socrata.com/foundry/data.cms.gov/2zuc-y5mm

My goals for this project are outlined below:

* Create and call at least 3 functions, at least one of which must return a value that is used

* Calculate and display data based on an external factor

* Connect to an external/3rd party API and read data into your app

* Analyze text/data and display information about it (ex: how many words in a paragraph)

* Visualize data in a graph, chart, or other visual representation of data

I want to use these goals to examine Medicare claims data across all surgical procedures reported (by HCPCS/CPT code) to see what insights can be gleaned from the data. Since it is a Jupyter Notebook, the data and project itself will be pretty heavily annotated, but in order to get my project to run, you will want to do the following:

### Running the Project Using Anaconda Navigator

- Download Anaconda Navigator (you can use this site - https://www.anaconda.com/products/individual) for your OS.
- Once downloaded and installed, you will want to run Navigator, and make sure the Jupyter Notebooks app is installed on whatever environment you'll be using ("base" is default).
- Once Jupyter Notebooks are installed (it will show "launch" instead of "install" if it has been installed) you will want to click on the "environments" tab.
- On this page, you can search packages by "Installed", "Not Installed", "All", etc. You will want to make sure the following packages are installed:
    + pandas
    + matplotlib
    + requests
    + numpy (although I believe this may be included in pandas/matplotlib).

- Finally, you will need to pull down my repository into a folder that your current environment has access to. If you have installed these dependencies, then you should be able to open the project in Jupyter Notebooks and run it without issue.

### Running the Project Using Pip

- You can download python to get started using this link: https://www.python.org/downloads/. You will need Python 3.7 or above installed to run.
- Once Python is installed, you'll want to download my repository and run the terminal. After navigating to the folder that the repository was downloaded to, you will start by installing Jupyter Notebook with the `pip install notebook` command. 
- From there, you'll also need to run the following commands to download the necessary libraries:
    + `pip install pandas`
    + `pip install matplotlib`
    + `pip install requests`
- Finally, you can run Jupyter Notebook by running `jupyter notebook`. You'll want to use the Jupyter Notebook UI to access the CMS_Data file. Then, on the Notebook itself, you can click `Cell > Run All` to run all cells and display the project information.

Thanks for taking a look at my project!

~Joel
