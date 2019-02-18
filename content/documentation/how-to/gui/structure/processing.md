+++
title = "Data reduction"
description = "Functionalities of the Data reduction tab"
weight = 103
+++

## The Data Reduction Tab
This tab allows to perform the data reduction from the raw .tof-file to the final S(q,t) output.
### The Process Panel
In this part of the GUI the input data and the treatment process can be specified.

1: Depending on the CASCADE-detector, it can be selected, which foil indices are active.

2: Depending on the spin echo time, the detector foils can be further restricted.

3: The measurements from the current environment can be selected, which should be treated in the defined way.

4: The phase correction is selected in this panel. Currently only the mask method is implemented properly. 

5: Resolution (used to normalize contrast for S(q,t)) and background measurement are specified here. 

6: Status bar of data reduction. From top to bottom (also performed in this order): Data import. Phase correction. Reduction. Post process. Left buttons are for running the corresponding script, right buttons for viewing the script.

![Example image](/img/gui/data_reduction_1.png#center)

### The Panel Panel
Allows to investigate the data in detail to find faulty fits or foils.

1: Select a mask for data reduction. It can be modified like in the mask tab.

2: The measurement (parameter), echotime and foil can be selected here. Measurement is a variable, if you performed two measurements at the same parameter.

3: Detector image of the current set of parameters.

4: Detector image with applied mask.

5: Time channel fit for current foil, mask and echo time.

6: Contrast for current foil and mask

![Example image](/img/gui/data_reduction_2.png#center)

### The Scripts Panel
Allows you to modify the scripts behind the four buttons Data import, Phase correction, Reduction and Post process from the Process panel.

1: Modify the script like in a text editor.

2: Update the GUI according to your changes.

3: Run the current script (like pushing the left button in the Process panel).

![Example image](/img/gui/data_reduction_3.png#center)