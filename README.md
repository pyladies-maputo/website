# website

Website PyLadies Maputo usando mynt generator

# Environment

To have the this website running locally, you must first, have `git`, and `python` installed and then follow the steps bellow:

## Clone the repository

```bash
$ git clone https://github.com/pyladies-maputo/website.git
```

If you use SSH

```bash
$ git clone git@github.com:pyladies-maputo/website.git
```

then, enter in the directory that contains the cloned repository to set the virtual environment:

```bash
$ cd website
$ python3 -m venv venv
```

Now, activate the virtual environment (venv) and install the required libraries

For Linux and MacOS users:

```bash
$ source venv/bin/activate
```

For Windows users:

```bash
$ venv\Scripts\activate
```

### Installation

```bash
pip install -r requirements.txt
```

### Run it

```bash
mynt gen src dist -d
mynt serve dist
```

And it must start a server listening on the PORT 8080, you can now open your browser and ether `http://localhost:8080` to preview it
