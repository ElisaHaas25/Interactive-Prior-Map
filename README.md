# Interactive-Prior-Map

The Jupyter Notebook "interactive_prior_map.ipynb" can be used to interactively create plots of two different prior probability distributions: either the generalized gamma gistribution (GGD) or the exponentially decreasing density distribution (EDSD), which is a special case of the GGD. The parameters for these plots are chosen based on their position in the sky and their respective HEALpixels. You can find them in the prior_summary.csv file.

First, you choose your model. There are three options: 

- only GGD
- only EDSD
- both GGD and EDSD

Now, you can choose wether you want the HEALPix colour scheme as background or an image of the Milkyway. 
If you want to set the plotting range of the prior yourself, klick the respecktive checkbox and adjust the range via sliders or type in the numbers by klicking on them (they should change by pressing enter). Otherwise the plotting range is being adjusted automatically.   


Then, you can select the mode. There are two options: 

- interactive output 
- manual output

The default mode is "manual input" (already selected). Here you can set the coordinates/HEALpixel yourself. To do this, you first select in the "Input"-field wether you want to enter the galactic longitude and latitude ("glon/glat") or the HEALpixel number ("HEALpixel"). Then based on what you chose, you can select the respective numbers either via sliders or you type them into the field next to the sliders. 

Example: you want to plot the GGD prior in the HEALpixel 5000. 

1. select "Model: GGD"   
2. choose the background and optionally adjust the plotting range
3. select "Mode: manual input"
4. select "Input: HEALpixel"
5. in the field "HEALpixel", type in "5000" or select "5000" via the respective slider. 

Then there is the other mode, the "interactive input". Here you can select a position via mouseklick. In the plot right to the map, the previously selected prior model should be plotted now. If you then click on another position, the plot changes.   

After making all adjustments, the desired output is produced by clicking on the "start"-button.

Required Python Packages: matplotlib, numpy, astropy, astropy-healpix, scipy, ipywidgets, ipython, csv



