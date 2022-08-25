# Pattern Recognition Course

Files related to course on pattern recognition.

## Setup

1. Setup your python environment using `venv`

Make sure you have python 3.x installed in your computers and know how to call it from the command line. To create a virtual environment (assuming your run python 3 using `python3` from the command line), execute the following command:

```
python3 -v venv env
```

This will create a directory called `env` (which is ignored here in the repository so you can generate your own).

2. Activate your environment

For Linux / Mac users:

```
source env/bin/activate
```

For Windows users:

```
env\Scripts\activate.ps1
```

If permission problems persist on Windows, you might have to run the following first:

```
env\Scripts\activate.ps1
```

3. Install the necessary dependencies.

For each of the following, make sure to run `pip install [package-name]`:

* jupyter
* pandas

4. Enter the directory `notebooks` and run the following command:

```
jupyter notebook .
```

5. Visit the running jupyter instance by pointing your browser to `http://localhost:8888` (usually this is ran automatically after doing item 4).
