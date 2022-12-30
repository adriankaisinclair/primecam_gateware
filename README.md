## primecam_gateware
Compiled design files for the Prime-Cam instrument's RFSoC based readout for kinetic inductance detectors. For more information about the readout see the conference proceeding https://arxiv.org/pdf/2208.07465.pdf. For more information about Prime-Cam https://www.ccatobservatory.org/

The Jupyter notebook contains the essential functionality to control the gateware compiled gatware. A more advanced version of the software to be deployed with Prime-Cam can be found at https://github.com/TheJabur/CCATpHive     

This design utilizes a custom compiled PYNQ v2.6 image. Contact adriansinclair@phas.ubc.ca for the image.

Repository table of contents:
1. tetra_vx.ipynb - Jupyter notebook which runs gateware and contains essential software functions
2. tetra_vxpy.bit - Compiled gateware bitstream 
3. tetra_vxpy.hwh - Hardware handoff file for bitstream  

Adrian Sinclair 2022
