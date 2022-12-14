# An improved version of the previous tool for image segmentation 

This tool will propose several processes for the automatic segmentation of images.
Have a look at the project's [Cancer Feature Analysis](https://github.com/Guyon-J/Cancer_Feature_Analysis/wiki/Welcome-to-the-Cancer-Feature-Analysis-wiki!) to get more information about the image analysis tools.


## Installation instructions
In [Fiji](https://fiji.sc/) window, open Plugins > Macros > Startup Macros... and copy and past the code >> __[here](https://raw.githubusercontent.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/main/Macro_Image_Segmentation)__ <<. 
Change the language into IJ1 Macro and save as .ijm file in the Fiji.app folder > macros > toolsets.

Select the tool in the "More Tools" menu (**>>**)


## Tool icons
1. HELP <br> <img align='left' src="https://github.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/blob/main/Image/Tool_Icons/1.png" height='40'/> Summary descriptions of the tool's tabs <br><br><hr>
2. Image Segmentation <br> <img align='left' src="https://github.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/blob/main/Image/Tool_Icons/2.png" height='40'/> Apply the choosen segmentation algorithm to delineate contourn (right click for open a dialog box to choose one algorythm and change parameters). <br><br><hr>
3. Core Area <br> <img align='left' src="https://github.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/blob/main/Image/Tool_Icons/3.png" height='40'/> Apply the segmentation algorythm to delineate core contourn (right click for open a dialog box to choose one algorithm and change parameters). <br><br><hr>
4. Skeletonize <br> <img align='left' src="https://github.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/blob/main/Image/Tool_Icons/4.png" height='40'/> Skeletonize from a binary ROI (Requires having the ROI of the total area in the last position in the ROI manager). <br><br><hr>

## Algorythm
<br> <img src="https://github.com/Guyon-J/Macro_for_Spheroid_Analysis_v2/blob/main/Image/algorythm.png" height='500'/><br>
A. Step-by-step presentation of the segmentation: (i) Raw image ; (ii) Image obtained from the subtraction of the filtered image by the image with a mask ; (iii) Contour of the image with Sobel filter ; (iv) Delineation of the different zones of the spheroid. B. Examples of segmentation with basic parameters. Scale = 50 ??m.
<br>

Source:<i> Joris Guyon. Nouveaux m??canismes du d??veloppement des tumeurs c??r??brales. Biologie cellulaire. Universit?? de Bordeaux, 2021. Fran??ais. NNT : 2021BORD0344 . tel-03576571 </i>
<br>
<br>

To try this macro, you can find samples __[here](https://github.com/Guyon-J/Macro_for_Spheroid_Analysis/tree/main/Images/Spheroid_Samples)__.


## How to Cite
<div itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0001-6692-2890" href="https://orcid.org/0000-0001-6692-2890" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">Guyon, J.</a>, Fernandez-Moncada, I., Larrieu, C., Bouchez, C., Pagano Zottola, A., Galvis, J., Chouleur, T., Burban, A., Joseph, K., Ravi, V., Espedal, H., R??sland, G. V., Daher, B., Barre, A., Dartigues, B., Karkar, S., Rudewicz, J., Romero-Garmendia, I., Klink, B., Gr??tzmann, K., Derieppe, M-A., Molini??, T., Obad, N., Leon, C., Seano, G., Miletic, H., Heiland, D., Mariscano, G., Nikolski, M., Bjerkvig, R., Bikfalvi, A., and <itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0002-0319-7617" href="https://orcid.org/0000-0002-0319-7617" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">Daubon, T.</a> 

Lactate dehydrogenases promote glioblastoma growth and invasion via a metabolic symbiosis. EMBO Mol Med (2022) e15343, [doi.org/10.15252/emmm.202115343](https://doi.org/10.15252/emmm.202115343). 


## Compatibility

This toolset was developed on window 10, and tested using ImageJ v1.53. Many features require installation of command line tools that may present future challenges on different operating systems.
