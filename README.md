# Chedotal_Lab_Head_Development
Python notebooks used in Blain et al., 2023, "A tridimensional atlas of the developing human head." 

This repository contains notebooks for the following:

*(1) Mask_Labels.ipynb*

Extract segmentation masks made in Syglass from raw TIFF images using tifffile, sci-kit image, and numpy. 

*(2) QECD_in_Folder.ipynb*

Perform quadric edge collapse decimation on a folder of meshes to reduce the filesize of each surface mesh, using pymeshlab. 

*(3) 3D_Print_Prep.ipynb*

Merge multiple mesh files into one and reconstruct it to prepare surface files for a single 3D printable STL file.  
