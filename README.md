# Statistical Methods Course
Statistical Methods is taught in the Metallurgical Engineering (MET E) department at the University of Utah as of Fall 2021. The course ID is MET E 3070. Code in Python, Mathematica, and possibly other languages are hosted in this repository. In general, these follow the sequential flow of lecture notes and are structured according to "Modules" in the Fall 2021 Canvas course. PDF versions of the Jupyter (i.e. Python) and Mathematica notebooks are also provided.

## Installation
Click <img src=https://user-images.githubusercontent.com/45469701/131147626-0a1e9748-d7ff-4f14-a079-afffed881777.png width=50> and <img src=https://user-images.githubusercontent.com/45469701/131147735-a5879b53-bd00-43a6-b08e-df76d73da99b.png width=200>. If GitHub Desktop is not already installed, follow the instructions to install it and then repeat the steps above. Press `Ctrl+Shift+P` to "pull" the most recent changes from the repository into the local copy ("clone") on your device.

## First time on GitHub?
For a basic introduction to git and GitHub, see the "LaTeX and GitHub" section of the following video [beginning at 6:22](https://www.youtube.com/watch?v=K7xbBEMm8I0&t=382s) until 12:19 (~6 minutes):

_Automating your research paper: Tips, Tricks, and Tools (how to be an amazing grad student!)_

<a href="https://www.youtube.com/watch?v=K7xbBEMm8I0&t=382s">
<img src=https://user-images.githubusercontent.com/45469701/131149663-2f702db1-1747-4a9c-805c-37b62d53a1f2.png width=300>
</a>

## New to Python?
I suggest that you [download Anaconda](https://www.anaconda.com/products/individual-d), [create a new environment](https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/) called e.g. mete-3070, and [install the dependencies](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-pkgs.html#installing-packages) (NumPy, SciPy, Matplotlib, and Jupyter notebook). I also recommend Dr. Taylor Sparks' YouTube course called [Intro to Python Programming for Materials Engineers](https://youtu.be/aoL3whRmSfc).

### Environments
Since many Python packages are written by different organizations, compatibility between packages is a non-trivial issue. Here is a blurb from the [conda docs](https://conda.io/projects/conda/en/latest/user-guide/concepts/environments.html) (Links to an external site.) about environments:

> A conda environment is a directory that contains a specific collection of conda packages that you have installed. For example, you may have one environment with NumPy 1.7 and its dependencies, and another environment with NumPy 1.6 for legacy testing. If you change one environment, your other environments are not affected. You can easily activate or deactivate environments, which is how you switch between them. You can also share your environment with someone by giving them a copy of your  `environment.yaml` file.

Creating a new environment gives you a clean slate that won't mess with other projects. The GUI instructions for creating a new environment are:

`Environment` tab --> `Create` --> enter `Name` (e.g. `mete-3070`) --> Choose `Python 3.8` --> `Create`

To switch to your new environment:

`Home` tab --> `Applications on ...` --> Click dropdown arrow and select `mete-3070` (or whatever you named your environment)

### Install Dependencies
To install the dependencies we'll be working with:

`Install` (see button within either Powershell Prompt or CMD.exe Prompt widget) --> `Launch` (again, either Powershell or CMD.exe) --> type the following command followed by the return key `conda install numpy scipy matplotlib`. Note that these are the dependencies for "Module 1", and other packages may be necessary as the course progresses.

To install Jupyter Notebook, click the `Install` button within the Jupyter Notebook widget.

Click `Launch` inside the Jupyter Notebook widget, navigate to a directory of your choice, and then `New` --> `Python 3` (Notebook).
