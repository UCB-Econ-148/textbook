# textbook
Textbook for Econ 148: Data Science for Economists at UC Berkeley. Can be viewed at econ148.org/textbook.

Content is stored in the content folder. Order of textbook can be changed from _toc.yml file. All required packages are in requirements.txt (generated using update_reqs.ipynb).

To update the textbook:
- Make any relevant changes to the content folder or _toc.yml.
- Build the jupyter book ([link](https://jupyterbook.org/en/stable/start/build.html)). You can preview you changes here.
- Push to the GitHub pages via running `ghp-import -n -p -f _build/html` on the command line ([link](https://jupyterbook.org/en/stable/start/publish.html)).

This textbook is a part of Rohan Jha's data science honors thesis. Code for the other portions of the data science honors thesis (including the package he built, `Stata2Python`) can be found in [this](https://github.com/rohanjha123/data-h195) GitHub repo.