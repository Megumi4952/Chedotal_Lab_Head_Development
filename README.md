# Chedotal_Lab_Head_Development
Python notebooks used in Blain et al., 2023, "A tridimensional atlas of the developing human head." 

This repository contains the following notebooks:

*(1) Mask_Labels.ipynb*

Extract segmentation masks made in Syglass from raw TIFF images using tifffile, sci-kit image, and numpy. 

*(2) QECD_in_Folder.ipynb*

Perform quadric edge collapse decimation on a folder of meshes to reduce the filesize of each surface mesh, using pymeshlab. 

*(3) Merge_Meshes_for_3DP.ipynb*

Merges multiple mesh files in a folder into a single file, binarizes it into isotropic voxels and exports a single tiff stack, using pymeshlab and vedo.  
