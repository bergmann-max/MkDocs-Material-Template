# MkDocs-Material Template 📄
This template for MkDocs Material allows to quickly create a website for documentation.
For full documentation visit
  * [MkDocs](https://www.mkdocs.org)
  * [MkDocs-Material](https://squidfunk.github.io/mkdocs-material/)
  * [Markdown](https://daringfireball.net/projects/markdown)

## Getting started

### Requirements

#### Python

Install [Python](https://www.python.org/) using your package manager of choice, or by downloading an installer appropriate for your system from [python.org](https://www.python.org/downloads/) and running it.

#### pip

If you're using a recent version of Python, the Python package manager, [pip](https://pip.pypa.io/en/stable/installing/), is most likely installed by default. However, you may need to upgrade pip to the lasted version:

    $ pip install --upgrade pip

If you need to install pip for the first time, download [get-pip.py](https://bootstrap.pypa.io/get-pip.py). Then run the following command to install it:

    $ python get-pip.py

### Installing MkDocs w/ MkDocs-Material

1. Install the necessary packages using pip:

        $ pip install mkdocs-material mkdocs[i18n] mkdocs-glightbox mkdocs-git-revision-date-localized-plugin mkdocs-table-reader-plugin

1.  Clone the repository:

        $ git clone git@github.com:bergmann-max/MkDocs-Material-Template.git

1.  Change your current working directory

        $ cd MkDocs-Material-Template

1.  Run the command to start a local server that hosts your MkDocs site

        $ mkdocs serve

1. Open up [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser, and you'll see the default home page being displayed        

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.    