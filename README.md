# Muckrock Document Cloud Addons - CS519 Spring 2022

# Brief Overview

Our project entailed building add-ons for the DocumentCloud platform, with the goal of users making use of the add-ons and also using them as examples to build their own add-ons. These add-ons live in their own repositories, and run as GitHub Actions. 

# Technical Overview

The technical architecture for the project is very simple. All code is written in Python, making use of the documentcloud package which is used to interact with the site's API. Some GitHub Action management is performed by modifying the attributes in the config.yaml files in each repository as well.

# Instructions to Run 

Each add-on can be ran locally for testing purposes. 

To do so, a user will clone the add-on's repository onto their machine, install the requisite python packages for that add-on from requirements.txt, and then can call main.py from the command line inputting the specified arguments in that add-on's readme.

In addition, the add-ons have been added to the production site and can be ran by any DocumentCloud user like shown in this example video:

https://muckrock.s3.amazonaws.com/files_static/2022/documentcloudvids/DocumentCloudRegEx.m4v 

# Deployment Instructions

With a valid DocumentCloud account, one can simply link their GitHub account and DocumentCloud accounts by following the prompts on the DocumentCloud site, link their repositories, and then will be able to run their own add-ons on the site. Note that for this to work properly, you must have your primary Github and MuckRock/DocumentCloud accounts set to use the same email address. 

# Links to Repositories

As our project involves making multiple GitHub Repositories that function as GitHub Actions for use as add-ons to the DocumentCloud functionality, 
we can't really have all of our code in this repository. As such, we will link to all of our individual repositories here:

Have been tested and deployed on our end as working GitHub Actions:

- Metadata Scraper: https://github.com/cam-garrison/documentcloud-metadata-grabber
- User uploads over time graphing: https://github.com/cam-garrison/doccloud-uploads-graph
- Find and link legal citations within documents: https://github.com/JamesKunstle/documentcloud-legal-citation-identifcation-addon 
- Regex Pattern Bank Addon for finding PII: https://github.com/JamesKunstle/documentcloud-multi-regex-pattern-bank-addon
- Multi Regex Addon: https://github.com/JamesKunstle/documentcloud-multi-regex-addon 
- Page Statistics: https://github.com/sooryu22/documentcloud-page-stats-addon
- Custom Metadata Scraper: https://github.com/DaveG77/documentcloud-custom-metadata-scraper-addon
- Redact Bottom Inch: https://github.com/DaveG77/documentcloud-redact-bottom-inch-addon
- Identify/Redact Bad Redactions: https://github.com/sooryu22/documentcloud-bad-redactions-addon
- N-Gram Graphing: https://github.com/cam-garrison/doccloud-n-gram-addon
- Simple Document Sentiment Analysis: https://github.com/JamesKunstle/documentcloud-sentiment-analysis-addon

Works in progress, not yet run as GitHub Actions:
- Nothing at the moment

# Add Users
To add yourself to the repository, open a Pull Request modifying `COLLABORATORS`, entering your GitHub username in a newline.

All Pull Requests must follow the Pull Request Template, with a title formatted like such `[Project Name]: <Descriptive Title>`
