# upcredAssignmentInstaScrpper
# Objective:
The objective of this assignment is to scrape a large number of Instagram profiles and extract
relevant details from them, specifically targeting profiles with over 2,000 followers from around
the globe. The aim is to gather a comprehensive dataset of such profiles to analyze various
aspects of Instagram usage, engagement, and user demographics.

# Tools and Technologies Used:
The working Environment , tools and technologies I used in building the model are as follows:
Working Environment: Anaconda Navigator, Jupyter Notebook.
Tools and Techniques : Selenium, Chrome-Driver, JSON
Programming Language: Python.
System OS: Windows 11.
Library: Insta-Loader.

# Developing the Model:
The Scrapping model has been developed in the form of two Jupyter Notebooks.
In this section I am going to discuss them as follows:
1st Notebook: insta_extractor.ipynb
This notebook contains the source code for opening the instagram in the virtual environment
and Login. So that the user can login virtually to scrape the profile data.
2nd Notebook: scraping_with_instaloader
This is the notebook which contains the main scrapping model divided into 3 kernels:
The Input kernel : After running this kernel user can enter the username of the instagram profile
that needs to be scrapped.
Printing Profile id: This kernel is only just printing the profile-id . It can be used to cross check
the availability of the profile.
The Output Kernel: The output kernel contains exact logic for scrapping the profile data. This
section of the model prints the important data about the profile and saves the information in the
form of a dictionary in the JSON file.

# Limitation and Future Scope:
In the above work, I have collected data of 100 profiles by using the above scrapped model. The
limitation of the above work is that the profile can be scrapped one by one, not bulk of profiles
altogether.
The future scope of the work is to make it efficient enough to scrape millions of data in lesser
time by using the automation technique, as in this model “no. of profile scrapped is directly
proportional to the time required”.

