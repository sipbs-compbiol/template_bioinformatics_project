# README.md `notebooks`

The `notebooks` folder might contain examples of [`Jupyter`](https://jupyter.org/) or [`RMarkdown`](https://rmarkdown.rstudio.com/) notebooks. These notebook formats are powerful, dynamic documents that interleave code and text. They can be very useful for:

- working through problems as a kind of "sketchpad"
  - the interactive nature of the document means that you can experiment with code and analyses quickly
- reusing ideas and analyses with new datasets
  - supporting _reusability_ and _reproducibility_
- presenting interactive analyses with dynamic widgets
  - enabling a reader to explore the data with no need for detailed technical knowledge

- mixing richly formatted text with code and output, and to save documents in other formats (e.g. `.pdf` and `.html`) 
  - enables _sharing_ with others and rapid publication
  - presenting analyses elegantly in a static way
  - writing webpages showing your work and analysis
  - host supplementary material online that is too large or cumbersome to include in a report or thesis
  - presenting the entire analysis or thesis in an interactive book form

Notebooks can be organised in many different ways: one subfolder per kind of notebook; a different subfolder for each topic addressed; no subfolders; and so on.

## Making a notebook available as a webpage in GitHub Pages

1. Save the `notebook` in `.html` format
2. Add and commit the `.html` pages to the GitHub repository
3. Add a link in the main landing `README.md` file or from another intersitital webpage to the HTML page built by GitHub Pages.

- [`Getting started with GitHub Pages`](https://docs.github.com/en/pages/getting-started-with-github-pages)



## Useful links

Below are links to tutorials and pages to help present your `notebooks`:

**GitPages:** Links n how to set up GitHub pages:
* What are GitHub pages and what features are available: https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages
* GitHub quick guide: https://docs.github.com/en/pages/quickstart
* www3Schools: https://www.w3schools.com/git/git_github_pages.asp

**Examples of GitHub pages:**
* _Present methods_: https://widdowquinn.github.io/2018-03-06-ibioic/
* _Present methods/documentation_: https://hobnobmancer.github.io/cazy_webscraper/
* _Present methods and supplementary data_: https://widdowquinn.github.io/SI_Hugouvieux-Cotte-Pattat_2021/

**Examples of intergrating `notebooks` into GitHub pages:**
* _Present a mixture of methods and results using `Jupyter notebooks`_:
    * _The directory in the repo where the `notebook` and HTML page are stored_: https://github.com/widdowquinn/2018-03-06-ibioic/tree/master/02-sequence_databases
    * _The resulting GitHub page_: https://widdowquinn.github.io/2018-03-06-ibioic/02-sequence_databases/05-blast_for_rbh.html

* _Present analyses and supplementary data using `Rmarkdown notebooks`_:
    * _The directory in the repo where the `notebook` and HTML page are stored_: https://github.com/HobnobMancer/pyrewton/tree/master/pyrewton/cazymes/evaluate_tools/report
    * _The resulting GitHub page_: https://hobnobmancer.github.io/pyrewton/pyrewton/cazymes/evaluate_tools/report/cazyme_prediction_tool_evaluation-2021-03-30.html

* https://htmlpreview.github.io/?https://github.com/cbernet/jupyter_web/blob/master/index.html
