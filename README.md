# Installation

###Prerequisites:

CWDocs is using MkDocs, static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file.

In order to use and build the docs page you'll need [Python 2.7](https://www.python.org/), [Python Package Indexer](https://pypi.python.org/pypi/pip)

Run these commands to check if you have these installed:
```
$ python --version
Python 2.7.2
$ pip --version
pip 8.1.0
```

Install the MkDocs package using pip and Material Design theme for MkDocs:
```
$ pip install mkdocs
$ pip install mkdocs-material
$ mkdocs --version
mkdocs, version 0.15.3
```
Go to your local directory, for example `c:\docs\` and clone this git repository
```
$ git clone https://github.com/gufu/cwdocs.git
```
While in `c:\docs\` folder run `mkdocs serve` command to start your local preview of CWDocs page.



# Usage