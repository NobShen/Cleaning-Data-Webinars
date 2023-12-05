# Cleaning-Data-Webinars




This repository contains material associated with the series
of webinars on cleaning data I deliver for Safari Online,
in association with my Addison Wesley book:

_Cleaning Data for Effective Data Science: Doing the Other 80% of the Work_

Excerpts from the book material will be utilized, as well
as both some of the same data sets and additional materials.

Please contact cleaning@kdm.training for more information on the 
book or suggestions about the webinar material.

Rough instructions:

>First do a git clone to local drive $HOME/Downloads
>Then create
>
>sudo apt update sudo apt upgrade

>Install pip for python3

Before installing the virtual environment, let's install pip. Pip is a package manager which helps to install, uninstall and upgrade packages for your projects.

To install pip for python 3 type:

>apt install python3-pip

Create virtual environment for python 3

Venv command is used in Python to create the virtual environment. The venv package is available in Ubuntu repository.

Let's first install venv package using the following command:

>apt install python3-venv

Now, to create a virtual environment, type:

>python3 -m venv my_env_project

The above command creates a directory named 'my_env_project' in the current directory, which contains pip, interpreter, scripts, and libraries.

$ ls my_env_project/
 bin  include  lib  lib64  pyvenv.cfg  share

You can now activate the virtual environment, type:

source my_env_project/bin/activate

Command prompt would change to your environment and will look as shown:

(my_env_project) linuxopsys@ubuntu:~$

Verify Virtual Environment

Run python command inside virtual environment to open the interpreter:

(my_env_project) linuxopsys@ubuntu:~$ python

Output
Python 3.8.5 (default, Jul 28 2020, 12:59:40)
[GCC 9.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.

To install a package inside the virtual environment, for example I am installing NumPy package:

Note: Some larger data sets that are associated with the book
and webinar may be kept at a separate repository.  This is a 
temporary organization, and will likely be updated later:

>https://bitbucket.org/davidmertz/sample-data
