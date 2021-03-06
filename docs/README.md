## Python in Physics Bootcamp -- Getting started

We will need to download and install a python distribution.  Every user has their own python distribution, which allows you to use whatever packages in python are necessary for your work.  Our industry-standard approach is to download the Anaconda python distribution, which bundles all the really important parts of the python universe into one place.  The package can be downloaded from [here](https://www.anaconda.com/download/).   If you right-click on the link and copy the link in your web-browser, you can usually paste the file into the command line.  We'll want to download the file using the command `wget` ("web get", I guess).  When I wrote this, you can also get the links [here](https://repo.anaconda.com/archive/).  You can then run the installer with the `source` command.
You can then run the installer with the `source` command.

	wget https://repo.anaconda.com/archive/Anaconda3-5.2.0-Linux-x86_64.sh
	bash Anaconda3-5.2.0-Linux-x86_64.sh

or on a terminal on a Mac

	curl -O https://repo.anaconda.com/archive/Anaconda3-5.2.0-MacOSX-x86_64.pkg
	open Anaconda3-5.2.0-MacOSX-x86_64.pkg
	
Windows can download the `.exe` file by clicking on the link on the site, like [this one](https://repo.anaconda.com/archive/Anaconda3-5.2.0-Windows-x86_64.exe).
	
Make sure you change the location of the python install to be a place where you have some disk space.  At the end of the installation process, and install script may ask if you want to append the startup commands to your `.bashrc` file.  You will want to say "yes" so that the version of python you use is the one that you just installed.  Then open a new terminal window to run your login file again.

Next, download our three Jupyter notebook files that we'll need for this tutorial.  You can get them as a single zip file [here](https://github.com/UofAPhysics/PythonBootcamp/blob/master/Notebooks.zip).  If you are using Linux, you can command-line access this with:

    wget https://github.com/UofAPhysics/PythonBootcamp/blob/master/Notebooks.zip
    unzip Notebooks.zip
	jupyter notebook
	
Alternatively, if you have the Anaconda navigator, you can open it up and select the Jupyter notebook.
	
    


