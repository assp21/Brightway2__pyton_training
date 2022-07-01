# Brightway2__pyton_training
Installation
Please install miniconda.

Then, in a command prompt or a terminal window (see Brightway2 docs if this is something new), enter the following:

conda create -n bw2 python=3.6
Then activate the bw2 environment using something like one of the following:

source activate bw2
activate bw2
Finally, instead the needed libraries:

conda install -q -y -c haasad -c conda-forge brightway2 jupyter jupyter_contrib_nbextensions jupyter_nbextensions_configurator
Ecoinvent
This seminar assumes you have access to the unit process data for Ecoinvent 2.2.

Background basics
There are some tutorials on Python listed here: https://docs.brightwaylca.org/intro.html#python

We recommend using ipython or jupyter notebooks instead of the plain python prompt - note that you will have to re-activate your bw2 environment in each new command/terminal window.

Spend some time browsing through the introduction and the example notebooks.
