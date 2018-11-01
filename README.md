# Introduction to Python

The purpose of this repository is to serve as an interactive "book" for a
thorough introduction to Python.

All examples and case studies are created with the **goal to prepare** the
student for further courses in the big and young field of **data science**.

The "chapters" are written as [Jupyter](https://jupyter.org/) notebooks which
are a de-facto standard for exchanging code and results among data science
professionals and researchers. As such they can be viewed in a plain web
browser (just click on the links in the list above).

However, it is recommended to **install Python and Jupyter locally** and run
the notebooks. This way, the student can play with the code and learn more
efficiently. Precise **installation instructions** are either in the
[00th notebook](00_start_up.ipynb) or further below.

Feedback is encouraged and will be incorporated.

Ideally, connect with me on [LinkedIn](https://www.linkedin.com/in/webartifex).


## Prerequisites

- understanding of the **English language**
- **basic mathematics** from high school (i.e., addition, subtraction,
  multiplication, division, and a bit more)
- ability / willingness to **invest 2-4 hours a day for a month** (see
  "ABC"-rule in the 00th notebook)


## Installation

To follow this course, a working installation of **Python 3.6** or higher is
expected.

To download the course's materials as a ZIP file, click on the green "Clone or
download" button on the top right on this website. Then, unpack the ZIP file
into a folder of your choosing (the folder should be under your personal
folder if you want to avoid some tedious configuation using the Anaconda option
below). Alternatively, use the [git](https://git-scm.com/) command-line tool
and clone this repository.

Since Jupyter notebooks have become a de-facto standard for communicating and
exchanging results in the data science community (both in academia and
business), the corresponding extensions have to be installed as well.

There are two recommended ways to install Python and Jupyter for this course.
The second approach is probably more beginner friendly.

### 1) Canonical

First, check the official
[Python installation instructions](https://www.python.org/downloads/) for your
operating system and install the latest version. This includes only the core
parts of Python and the Standard Library. Then, using the `pip` or `pipenv`
command-line tools install the *jupyter* package (see the notes at the bottom
of this [link](https://jupyter.org/install)), ideally using a
[virtual environment](https://docs.python.org/3/library/venv.html).

After installation, open a terminal, switch to the folder created as above, and
type `jupyter notebook`, possibly after activating the virtual environment
(e.g., with entering `source venv/bin/activate`). Then a new tab should open in
your web browser and display a file overview type of page. Go to the folder
where you unpacked the downloaded ZIP archive and start working through the
notebooks in order.

### 2) Anaconda

Another very popular way is to use a Python distribution that comes
pre-packaged with a lot of the so-called "scientific" packages (*jupyter* being
among them) such as the
[Anaconda Distribution](https://www.anaconda.com/download/). Just go to the
download page and install the latest version for your operating system.

Then you will find an entry in your start menu like below. Click on it and a
new tab in your browser will open, where you can switch between folders as you
could in your computer's default file browser. Go to the folder where you
unpacked the downloaded ZIP archive and start working through the notebooks in
order.

<img src="static/anaconda.png" width="40%">
