# Workshop static site

This website provides documentation and information about the contents of the workshop.

## Building the site

To run the website locally use, you fist have to install dependencies through python and pip:

```shell
# sets up a virtual environment and installs dependencies there
$ pip install virtualenv
$ virtualenv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

Then run it with:

```shell
# Build site
$ mkdocs serve
```
