This is the documentation for [Drupal in a Day](https://drupalinaday.org). The
documentation is formatted in Markdown (MD) and reStructuredText (RST) and can 
be rendered into HTML or PDF using [Sphinx](http://www.sphinx-doc.org).

**To contribute, you do not need Sphinx**, especially if you write in Markdown;
there are plenty of tools that render Markdown while you edit and it is very 
readable in its plain form (the same, though to a lesser extent, is true for 
RST).

If you do wish to install Sphinx, instructions are below.

## Project structure
The documentation is set up in versions for each supported language. You find 
folders for each language at the top level. Currently, that is only Dutch (nl), 
although we plan to support English as soon as possible.
 
Each language directory is a Sphinx project in its own right. All translations
are expected to follow the same file structure. Source files are contained in 
(language dir)/source. Build directories are ignored in the root .gitignore 
file.

## Preparing to do your own build

### Install Sphinx on Mac
To install Sphinx on the Mac you need to have 
[pip](https://en.wikipedia.org/wiki/Pip_(package_manager)) available, the Python 
package manager. You can install pip through [homebrew](https://brew.sh).

    $ brew install pip

After installing pip, you install sphinx by issuing:

    $ pip install Sphinx

Proceed to the section [Clone the theme](#clone-the-theme).

### Install Sphinx on Windows/Linux
@todo. Please issue a pull request for these platforms if you can. Basics 
should be the same; install pip, install Sphinx.

Proceed to the section [Clone the theme](#clone-the-theme).

### Install the theme
In order to build the docs, you will also need the 
[Read the Docs Sphinx theme](https://github.com/rtfd/sphinx_rtd_theme). Since 
you've already installed pip, this is a simple one-liner:

    $ pip install sphinx_rtd_theme

## Building the docs
There are Makefiles in each language subdirectory. These are standard Sphinx
build files, which means you can build using:

    $ make html

or

    $ make pdf
    
**If you've used the Mac installation instructions**, chances are you installed
Sphinx in brew's Python 3 environment, not in macOS's default python 2.7 
environment. Issuing the above commands will have python complain it can't find 
the Sphinx module. In that case, you can amend the above commands to say you 
want to use Python 3:

    $ make html SPHINXBUILD="python3 -msphinx"
