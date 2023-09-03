# gprMax Model Examples

This folder contains examples of several models run on Jupyter Notebooks with the gprMax-devel kernel. 

## Models

### Cylinder A_Scan 2D
* **Model Files:**
  - `cylinder_Ascan_2D.in`: This is the input file containing instructions on how to build the model.
  - `cylinder_Ascan_2D.h5`: This is the output file after running the model on the Jupyter Notebook.
  - `cylinder_half_space.vti`: This is the 3D geometry output file of the A_Scan, which is used to visualize the model in Jupyter Notebook.
  - `cylinder_Ascan_2D_notebook.ipynb`: This is the Jupyter Notebook on which the model of the A_Scan of a cylinder is built and run. The A_Scan is plotted in this notebook along with the 3D model.

### Cylinder B_Scan 2D
* **Model Files:**
  - `cylinder_Bscan_2D.in`: This is the input file containing instructions on how to build the model.
  - `cylinder_Bscan_2D*.h5`: These are the output files after running the model on the Jupyter Notebook. These range from 1 to 10.
  - `cylinder_Bscan_2D_merged.h5`: This is the merged output file from the 10 output files after running the model.
  - `cylinder_Bscan_2D5.vti`: This is the 3D geometry output file of the B_Scan, which is used to visualize the model in Jupyter Notebook.
  - `cylinder_Bscan_2D_notebook.ipynb`: This is the Jupyter Notebook on which the model of the B_Scan of a cylinder is built and run. The B_Scan is plotted in this notebook along with the 3D model.

### GSSI 1500 Antenna Model
* **Model Files:**
  - `GSSI_1500_antenna_Bscan.in`: This is the input file containing instructions on how to build the model.
  - `GSSI_1500_antenna_Bscan.h5`: This is the output file after running the model on the Jupyter Notebook.
  - `antenna_like_GSSI_1500.vti`: This is the 3D geometry output file of the GSSI 1500 antenna, which is used to visualize the model in Jupyter Notebook.
  - `GSSI_1500_antenna_Bscan.ipynb`: This is the Jupyter Notebook on which the model of the GSSI 1500 antenna is built and run. The B_Scan is plotted in this notebook along with the 3D model.

### Hertzian Dipole in Free Space
* **Model Files:**
  - `hertzian_dipole_hs.in`: This is the input file containing instructions on how to build the model.
  - `hertzian_dipole_hs.h5`: This is the output file after running the model on the Jupyter Notebook.
  - `hertzian_dipole_hs_notebook.ipynb`: This is the Jupyter Notebook on which the model of a hertzian dipole in free space is built and run. The A_Scan of this is plotted in this notebook.

### Magnetic Dipole in Free Space
* **Model Files:**
  - `magnetic_dipole_hs.in`: This is the input file containing instructions on how to build the model.
  - `magnetic_dipole_hs.h5`: This is the output file after running the model on the Jupyter Notebook.
  - `magnetic_dipole_hs_notebook.ipynb`: This is the Jupyter Notebook on which the model of a magnetic dipole in free space is built and run. The A_Scan of this is plotted in this notebook.
