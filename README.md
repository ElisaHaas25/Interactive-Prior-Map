# Interactive-Prior-Map

The Jupyter Notebook "Interactive Prior Map" can be used to interactively create plots of two different prior probability distributions: either the generalized gamma gistribution (GGD) or the exponentially decreasing density distribution (EDSD), which is a special case of the GGD. (-cite papers-) The parameters for these plots are chosen based on their position in the sky and their respective HEALpixels. You can find them in the prior_summary.csv file.

First, you choose your model. There are three options: 

- only GGD
- only EDSD
- both GGD and EDSD

Then, you can select the mode. There are two options: 

- interactive output 
- manual output

The default mode is "manual input" (already selected). Here you can set the coordinates/HEALpixel yourself. To do this, you first select in the "Input"-field wether you want to enter the galactic longitude and latitude ("glon/glat") or the HEALpixel number ("HEALpixel"). Then based on what you chose, you can select the respective numbers either via sliders or you type them into the field next to the sliders. 

Example: you want to plot the GGD prior in the HEALpixel 5000. 

1. select "Model: GGD"   
2. select "Mode: manual input"
3. select "Input: HEALpixel"
4. in the field "HEALpixel", type in "5000" or select "5000" via the respective slider. 

Then there is the other mode, the "interactive input". Here you can select a position via mouseklick. If you click on "interactive input", a window should pop up. Put the window on fullscreen. Then click on the desired position in the galactic map. In the plot right to the map, the previously selected prior model should be plotted now. If you then click on another position, the plot changes.   

