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

### Running the Project Using Mini Conda

Note: If you wish to use pip, the dependencies are included below, but installation instructions are only included for mini conda (to avoid having to download the rather large Anaconda Navigator).

- You can download mini conda from here - https://docs.conda.io/projects/continuumio-conda/en/latest/user-guide/install/download.html. Just choose your OS, and follow the installation prompts (more options for customizing your installation are on the above site as well).
- Once conda is installed, you may want to create and activate a new environment to run this project using the following commands:
    +"conda create -n name_of_my_env python" - This will create a minimal environment with only Python installed in it. 
    + To put your self inside this environment run: "source activate name_of_my_env" On Windows the command is:"activate name_of_my_env"
- You can install Jupyter Notebook using the command "conda install notebook". The pip command is "pip install notebook".
- You will want to install all dependencies; you can do so using the "conda install" command, followed by the name below:
    + pandas (Note: pandas documentation also recommends installing "setuptools", "python-dateutil" and "pytz" for best performance).
    + matplotlib
    + requests
    + numpy
- To verify your packages, you can use the "conda list" command to pull up a list of all packages. Once all libraries above are installed, you can clone my repository to a folder accessible by your python environment and run Jupyter Notebook ("jupyter notebook"), and use the Jupyter Notebook interface to access my repository, opening the "CMS Data" notebook.

Thanks for taking a look at my project!

~Joel
