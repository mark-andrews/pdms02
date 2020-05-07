There are many ways to install and set up Python and many ways to use Python. I will be following the one that I find the easiest and most reliable and best suited for scientific applications. I'll call this the pip-virtualenv-jupyter way. Other ways of installing and using Python are possible, and I will mention them in the course, but it is best to stick to just one way for a course like this, and I think this is the best way.

In terms of setup, there are around five main steps. These steps are the same on Windows, MacOS, Linux.

1. Install Python 3.8
2. Pip install `virtualenv`
3. Create a virtual environment.
4. Install whatever packages are needed with pip, which can be done at any time from then onwards.
5. Launch jupyter notebook

Below I describe how to do this for Windows and MacOS now. Personally, I use Linux, but I won't describe the steps for Linux unless someone wants me to, because I will assume that almost everyone will be using Windows or Macs.


# Windows

## Step 1: Install Python 3.8

Go to https://www.python.org/downloads/ and download the Python 3.8.3. installer.

Trying this today on a Windows machine, I got the installer at the bottom of the page at https://www.python.org/downloads/release/python-383rc1/.
I used the `Windows x86-64 executable installer`.

Then you install that as normal, i.e. double click the installer. On the opening dialog box, it might give you the option to 'Add Python 3.8 to PATH'. I said yes to this.

Now, open a DOS shell and type `where python`. You should see something like this.

```
C:\Users\psy3andrem> where python
C:\Users\psy3andrem\AppData\Local\Programs\Python\Python38\python.exe
```

The do `where pip` and you should see something like this.

```
C:\Users\psy3andrem> where pip
C:\Users\psy3andrem\AppData\Local\Programs\Python\Python38\Scripts\pip.exe
```

And check the version with `python --version`. You should see something like this.

```
C:\Users\psy3andrem>python --version
Python 3.8.2
```

## Step 2: Install virtualenv

Using the pip installer, install the virtualenv package by typing this command at the DOS command prompt. (The $ indicates the command prompt)

```
$ pip install virtualenv --user
```

## Step 3: Create a virtual environment

You can have as many virtual environments as you want. Each is a separate Python installation. We will create one for this course. We will call it `py4datascience_venv`, but we can call it anything we want.

```
$ python -m venv py4datascience_venv
```

This will create the virtual environment in the working directory of the DOS session. Unless you change it, it will be your home directory.
Now, we need to activate the virtual environment. You do this

```
$ py4datascience_venv\Scripts\activate.bat
```

If that worked, your prompt should now look something like this.

```
(py4datascience_venv) C:\Users\psy3andrem>
```

## Step 4: Install packages

Now, we will install some packages. There are tens of thousands to choose from. We will start with some key packages, which we will install with pip.

```
$ pip install jupyter numpy scipy pandas
```

## Step 5: Launch Jupyter

Now we launch a Jupyter notebook.

```
$ jupyter notebook
```

Doing that should open your browser with a Jupyter notebook session. What this is and how to use it is another matter.


# MacOs

## Step 1: Install Python 3.8

Go here https://www.python.org/downloads/mac-osx/ and get the installer.
The latest 3.8.3 installer package is here https://www.python.org/ftp/python/3.8.3/python-3.8.3rc1-macosx10.9.pkg

Install that as usual on a Mac.

Now, in the Mac's terminal, check the installation. (The $ here means it is is terminal command prompt).

```
$ which python3
/usr/local/bin/python3
```

```
$ which pip3
/usr/local/bin/pip3
```

```
$ python3 --version
Python 3.8.3rc1
```

```
$ pip3 --version
pip 19.2.3 from /Library/Frameworks/Python.framework/Versions/3.8/lib/python3.8/site-packages/pip (python 3.8)
```

## Step 2: Install virtualenv

```
$ pip3 install virtualenv
```

## Step 3: Create a virtual environment

You can have as many virtual environments as you want. Each is a separate Python installation. We will create one for this course. We will call it `py4datascience_venv`, but we can call it anything we want.

```
$ python3 -m venv py4datascience_venv
```

Now activate that virtual environment.

```
$ source py4datascience_venv/bin/activate
```

Now your prompt should look something like this.

```
(py4datascience_venv) $
```

## Step 4: Install some packages

Now, we will install some packages. There are tens of thousands to choose from. We will start with some key packages, which we will install with pip.

```
$ pip install jupyter numpy scipy pandas
```

## Step 5: Launch Jupyter

Now we launch a Jupyter notebook.

```
$ jupyter notebook
```

Doing that should open your browser with a Jupyter notebook session. What this is and how to use it is another matter.

# Additional packages

```
pip install seaborn plotnine sklearn numba statsmodels rpy2 sympy
```
