# An improved version of the previous tool for image segmentation 

This tool will propose several processes for the automatic segmentation of images.
Have a look at the project's [Cancer Feature Analysis](https://github.com/Guyon-J/Cancer_Feature_Analysis/wiki/Welcome-to-the-Cancer-Feature-Analysis-wiki!) to get more information about the image analysis tools.


## Installation instructions
In [Fiji](https://fiji.sc/) window, open Plugins > Macros > Startup Macros... and copy and past the code >> __[here](https://raw.githubusercontent.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/main/Macro_Image_Segmentation?token=GHSAT0AAAAAABZ6IWOX5SRPW5S5RUQDKTVKY2JPJXA)__ <<. 
Change the language into IJ1 Macro and save as .ijm file in the Fiji.app folder > macros > toolsets.

Select the tool in the "More Tools" menu (**>>**)


## Tool icons
1. HELP <br> <img align='left' src="https://github.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/blob/main/Image/Tool_Icons/1.png" height='40'/> Allows simultaneous analysis of multiple spheroid images. It is possible to choose the area to quantify in the dialog box. Combination of the two following tool. <br><br><hr>
2. Image Segmentation <br> <img align='left' src="https://github.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/blob/main/Image/Tool_Icons/2.png" height='40'/> Apply the choosen segmentation algorithm to delineate contourn (right click for open a dialog box to choose one algorithm and change parameters). <br><br><hr>
3. Core Area <br> <img align='left' src="https://github.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/blob/main/Image/Tool_Icons/3.png" height='40'/> Apply the segmentation algorithm to delineate core contourn (right click for open a dialog box to choose one algorithm and change parameters). <br><br><hr>
4. Skeletonize <br> <img align='left' src="https://github.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/blob/main/Image/Tool_Icons/4.png" height='40'/> Skeletonize from a binary ROI (Requires having the ROI of the total area in the last position in the ROI manager). <br><br><hr>

## Algorythm
<br> <img src="https://github.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/blob/main/Image/algorythm.png" height='300'/><br>
A. Step-by-step presentation of the segmentation: (i) Raw image ; (ii) Image obtained from the subtraction of the filtered image by the image with a mask ; (iii) Contour of the image with Sobel filter ; (iv) Delineation of the different zones of the spheroid. B. Examples of segmentation with basic parameters. Scale = 50 μm.

Joris Guyon. Nouveaux mécanismes du développement des tumeurs cérébrales. Biologie cellulaire. Université de Bordeaux, 2021. Français. NNT : 2021BORD0344 . tel-03576571

To try this macro, you can find samples __[here](https://github.com/Guyon-J/Macro_for_Spheroid_Analysis/tree/main/Images/Spheroid_Samples)__.
<br>

## How to Cite
<br> [<img align='right' src="https:" height='75'/>](https://)
<div itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0001-6692-2890" href="https://orcid.org/0000-0001-6692-2890" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">Guyon, J.</a>, Røsland, G. V., Bikfalvi, A., and <itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0002-0319-7617" href="https://orcid.org/0000-0002-0319-7617" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">Daubon, T.</a> 

Title. Journal, XXX, [DOI](https://) (2022). 


## Compatibility

This toolset was developed on window 10, and tested using ImageJ v1.53. Many features require installation of command line tools that may present future challenges on different operating systems.
