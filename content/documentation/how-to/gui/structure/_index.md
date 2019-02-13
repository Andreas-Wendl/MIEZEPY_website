+++
title = "Structure of the GUI"
description = "Launching the MIEZEPY GUI and initial impresions"
weight = 82
+++


### GUI Elements
Some of the described functionalities are also available over the tabs at the top. We will focus on the six main tabs on the left side of the GUI.
#### Environments
This tab provides a list of all environments, which have been created in your project. New environments can be added or removed via the +/- buttons on the top left.
#### Data Loading
This tab allows to load data from .tof files to the environment, which is currently selected in the environments-tab.
#### Masks
Allows you to create and edit new masks for data reduction.
#### Skrips
Allows you individualize your data reduction via the GUI and execute the corresponding scripts. 
##### - Process
This panel allows to select the foils and echo times, which should be considered for the data-reduction. Furthermore, the datasets can be selected, which should be analyzed. For phase correction, there is currently one working option: "Use mask method". It determines the phase per pixel from the reference measurement using the provided mask. For all the considered measurements, now the time-channels are shifted to correct for phase-rings.

Under reduction setting, you can select the reference and background measurement as well as the mask, which should be selected for reduction.

##### - Panel

##### - Scripts
It is also possible to edit these skripts and insert an additional skrip to execute after the data reduction.
#### Results Plotting

#### Saving and Loading

{{% children depth="2" %}}
