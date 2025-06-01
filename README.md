# Oshani Seneviratne - Academic Website 

## Changing the top-level information

The index page content is available in /content/authors/admin/_index.md file.

## Importing Publications

Please check [this guide](https://docs.hugoblox.com/tutorial/resume/step-3/) on how to importing publications.

1. Use a bibtex file named publications.bib. 
2. If not done already, in the GitHub repository, click the _Settings_ tab at the top of the page, click _Actions_ _>_ _General_ in the left menu, choose _Allow_ and click _Save_.
3. _.github/workflows/import-publications_ does the magic of importing the publications. 
4. At the root of your GitHub repository, click _Upload Files_ and select the publications.bib file to upload to GitHub.
5. GitHub will now import the publications from Bibtex. Within a minute or two, GitHub will create a Pull Request.
6. If the changes look okay, click _Merge_ and then _Confirm Merge_.
7. In a few minutes, the website should automatically update to display the new publications.

## Credit 

This Website was adapted from [Hugo Academic CV Theme](https://github.com/HugoBlox/theme-academic-cv)
