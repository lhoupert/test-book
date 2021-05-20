# test-book

Test repository for online publishing of jupyterbooks using GitHub Pages

## Steps
1. Copy the book content in the html folder (e.g. `cp -R ../../Repos_fork/from-python-to-numpy/jupyter-book/_build/html . `)

1. Remove unnecessary files (e.g. `rm html/book.html html/01-preface.html`)

1. Install ghp-import `pip install ghp-import`

1. Publish the book online `ghp-import -n -p -f ./html`


## More
More info on how to publish a jupyter-book with gh-page [[here](https://jupyterbook.org/publish/gh-pages.html)]

More info on how to publish on a custom (sub)domain [[here](https://stackoverflow.com/questions/46455900/subdomain-of-website-for-github-pages-project)]
