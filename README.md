# VAI_DL_Models

Custom made models for VAI specific datasets. 2D CellPose models can be used in Python scripts, the Cellpose GUI, and the CellPose QuPath extension. **CellPose3 models are not compatible with CellPose-SAM or Cellpose2 environments.**

In the CellPose3_Models folder there are:

- two generalized models for detecting adipocytes in H&E RGB images collected on the Aperio scanner (V2 is a bit more generalized than V1)
- Microglia_largeZ_V2: 2D model with stitching to generate 3D objects. Created for detecting the microglia in ZF embryos collected from the Andor DragonFly Spinning Disk with ~4.0 um step size (refer to the OIC-136 Microglia GitHub repo for example on how to use)
- RBC_V10: 2D model to detect blood cells stained with a Geisma stain and imaged with a color camera on the Zeiss AxioScan

One StarDist model for detecting lipid droplets in 3D with from images acquired on the LSM880 with AiryScan. Needs to be used with a python script. See OIC-90 Lipid droplets for example on how to use and the env requirements for StarDist with GPU support.
