# step by step

Strongly recommend that don't miss any dependency.
See steps and requirements below
>https://github.com/facebook/Surround360/tree/master/surround360_render

Some dependencies always have three steps like

>1.git clone
>2.cd ///
>3.cmake and make ( | config)
Some dependencies would need install some basic denpendencies before install itself.

# Install Halide

In the official installing tutorial, we should 'make -j8' for it in the end.
surround360_render's README file miss this last step.

# python-wxgtk2.8 on ubuntu

We need this 'old' wheel for it is Gooey's dependency.
See below in answer 3
>https://askubuntu.com/questions/789302/install-python-wxgtk2-8-on-ubuntu-16-04

Use 'apt-get':
Add needed repository and update package list
>sudo add-apt-repository ppa:nilarimogard/webupd8

Update the package index:
>sudo apt-get update

Install it
>sudo apt-get install python-wxgtk2.8

# psutil

Gooey also need 'psutil' lib.

Install it
>pip install psutil

# gooey

Just in surround360_render's README.md

# COLMAP

Be careful about some basic dependencies. Go step by step with the official tutorial.

# sudo(root)

In some steps, 'sudo' command should be used.

**Tested successfully in Ubuntu 16.04 LTS**
