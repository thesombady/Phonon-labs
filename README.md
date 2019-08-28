# Phonon-labs
Updated 25.08
### Prerequisite
Jupyter notebook installed with packages *scipy*, *numpy* and *matplotlib*
### Before you start
Before you start you will have to istall *ipwidgets* package. So follow the steps at this homepage:[https://ipywidgets.readthedocs.io/en/latest/user_install.html](https://ipywidgets.readthedocs.io/en/latest/user_install.html).

### Usage
Download both *RunnerPhonon.ipynb* and *cphonon.ipynb* and open *RunnerPhonon.ipynb* in your notebook.
Left click on the first cell containing *%run cphonon.ipynb* on the first line. Then press "ctrl + enter" two times on your keyboard. It will run the program in the *cphonon.ipynb* and start the interactive lab. If something does not work, please report to Andris.
The output just below the cell should look like this:

![alt text](https://github.com/AndrissP/Phonon-labs/blob/master/Example.png "Logo Title Text 1")

The output contains two figures, many widgets that control the figures. Widgets are there to be touched and moved. The two figures should automatically update whenever you change some position of a widget. The lowest bottom *"Create animation"* will create an animation with the chosen parameters. It does not happen instanty but takes from a few up to 30 seconds. Please be patient. The creation time depends highly on the frequency $\omega$. If the frequency is low (for example < 1 our unit) the animation will be creating more frames, thus taking longer time. You can usually increase the frequency and not changing the physics much by increasing the spring constant $\gamma$. 

I might happen that the output is put in a small window where you have to scrole down to see something and which is very uncomfortable. To solve this, on the command line press Cell/Current Outputs/ Toggle Scrolling and reexecute the *%run cphonon.ipynb* cell. Now the output should be distributed all the way bellow the input cell.


#### Issues:
* Open-ends does not work at all

* No animation yet

* Number of particles should be even number when boundary conditions are periodic and Masses are different. Otherwise it is not periodic.

* No additional phase plot

### If you want to see what is inside
If you want to see what the program really does, open also *cphonon.ipynb*. You can run cell by cell by clicking *"ctrl + enter"*. You can also uncomment cell containing the variables (for example containg only #A) and run these cells to see the outpts of each cell. Shortcut for (un-) commenting is *"ctrl + /"*. You can also add your own code add print your own variables. 
