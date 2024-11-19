# nrrd2tiff
Convert an .nrrd micro-CT (XRM) dataset to a .tiff stack for upload to MorphoSource    
*Last updated 17 Nov 2024*

Jupyter Notebook and python3 script to convert an .Nrrd 3D volume file exported from 3D Slicer into a zipped tiff stack for upload to MorphoSource. This script was recently created and is being tested to ensure reliability of outputs when compared with tiff stacks produced in Fiji. So far, it has been tested with CT data produced by Zeiss Versa Xradia 620. If you use this code and encounter any issues with the tiff stacks produced, please open an issue so it can be resolved.

<p align="center">Demo slice sweep: a stack of 2D tiffs created from a 3D volume of <i>Theobroma cacao</i> (cacao, the source of chocolate).</p> 
<p align="center">
<a href="url"><img src="https://github.com/aubricot/nrrd2tiff/blob/main/demo_imgs/thecac_slicesweep_github_demo.gif" align="center" width="600" ></a></p> 

<p align="center">Example 2D tiff slice of <i>Theobroma cacao</i> (cacao, the source of chocolate) created from a 3D volume.</p>
<p align="center">
<a href="url"><img src="https://github.com/aubricot/nrrd2tiff/blob/main/demo_imgs/thecac_tiffslice_github_demo.png" align="middle" width="400" ></a></p>   

<p align="center">Example 3D volume rendering of <i>Theobroma cacao</i> (cacao, the source of chocolate) created from an nrrd file in 3D Slicer.</p>
<p align="center">
<a href="url"><img src="https://github.com/aubricot/nrrd2tiff/blob/main/demo_imgs/thecac_volren_github_demo.png" align="middle" width="400" ></a></p>   
