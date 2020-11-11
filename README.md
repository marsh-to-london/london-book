# Как переехать в Лондон и не сойти с ума?

This cookiecutter creates a simple boilerplate for a Jupyter Book. The website address is https://marsh-to-london.netlify.app. 

## Usage

### Building the book

If you'd like to develop on and build the Как переехать в Лондон и не сойти с ума? book, you should:

- Clone this repository and run
- Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
- (Recommended) Remove the existing `Как переехать в Лондон и не сойти с ума?/_build/` directory
- Run `jupyter-book build Как переехать в Лондон и не сойти с ума?/`

A fully-rendered HTML version of the book will be built in `Как переехать в Лондон и не сойти с ума?/_build/html/`.

### Hosting the book

The html version of the book is hosted on the `gh-pages` branch of this repo. A GitHub actions workflow has been created that automatically builds and pushes the book to this branch on a push or pull request to main.

If you wish to disable this automation, you may remove the GitHub actions workflow and build the book manually by:

- Navigating to your local build; and running,
- `ghp-import -n -p -f Как переехать в Лондон и не сойти с ума?/_build/html`

This will automatically push your build to the `gh-pages` branch. More information on this hosting process can be found [here](https://jupyterbook.org/publish/gh-pages.html#manually-host-your-book-with-github-pages).

## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/marsh-to-london/my-book/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
