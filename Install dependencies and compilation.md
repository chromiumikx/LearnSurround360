1 step by step

See steps and requirements below
>https://github.com/facebook/Surround360/tree/master/surround360_render

Strongly recommend that don't miss any dependency.

Some dependencies always have three steps like
>1 git clone
>2 cd ///
>3 cmake and make ( | config)
Some would need install some denpendencies before install itself.

2 Install Halide

In the official installing tutorial, we should 'make -j8' for it in the end.
surround360_render's README file miss this last step.

3 python-wxgtk2.8 on ubuntu

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

5 psutil

Gooey also need 'psutil' lib.

Install it
>pip install psutil

4 gooey

Just in surround360_render's README.md

6 COLMAP

Be careful about some basic dependencies. Go step by step with the official tutorial.

7 sudo(root)

In some steps, 'sudo' command should be used.

(Tested successfully in Ubuntu 16.04 LTS)
