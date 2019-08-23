# Phonon-labs
### Prerequisite
Jupiter notebook installed with packages *scipy*, *numpy* and *matplotlib*
### Before you start
Before you start you will have to istall *ipwidgets* package. So follow the steps at this homepage:[https://ipywidgets.readthedocs.io/en/latest/user_install.html](https://ipywidgets.readthedocs.io/en/latest/user_install.html).

### Usage
Download both *RunnerPhonon.ipynb* and *cphonon.ipynb* and open *RunnerPhonon.ipynb* in your notebook.
Left click on the first cell *%run cphonon.ipynb* and press "ctrl + enter" on your keyboard. It will will run the program in the *cphonon.ipynb* and start the interactive lab.
The output just below the cell should look like this (I have changed some outlines but the output is similar):

![alt text](https://github.com/AndrissP/Phonon-labs/blob/master/Example.png "Logo Title Text 1")

The output contains at this moment two figures and many widgets. Widgets are there to be touched and moved. The output should automatically update whenever you change some position of a widget.

#### Issues:
* Not all widget names are yet intuitive and self-explanatory. Not all of them are working as they should work (*Mode number*, for example does not depend on the number of particles *N*)

* No animation yet

* Open-ends does not work at all

### If you want to see what is inside
If you want to see what the program really does, open also *cphonon.ipynb*. You can run cell by cell by clicking ctrl + enter". You can also uncomment shells containing the variables (for example containg only #A) and run these cells to see the outpts of each cell. Shortcut for (un) commenting is "ctrl + /". You can also add your own code add print your own variables. 
