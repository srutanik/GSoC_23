<p align="center">
  <img src="media/readme-header.png">
</p>

## 💻 **Google Summer of Code 2023**:


* **Project Name:** Create a gprMax Custom Kernel for Jupyter Notebook

* **Mentors:**
  - Rania Patsia
  - John Hartley

## ✍🏼 **PROJECT DESCRIPTION**:

We create a custom gprMax kernel in the Jupyter Notebook which contains all the necessary modules and files from the gprMax installation that can be used within the Jupyter Notebook.

## 📂 **FILES**:

1. `install_notebook_dependencies.py` - Used for installing the gprMax-devel kernel on Jupyter Notebook.
2. `3D_visualization_toolbox` - Contains a custom 3D visualization function using the PyVista python library to show the geometry output of the model.
3. Modified gprMax files - Adjusted relative imports in these files from the gprMax-devel branch to resolve errors.
4. Test Models Notebooks - Files like `cylinder_Ascan_2D` and others, each containing a test notebook showcasing gprMax usage in notebooks.

Each folder has its own README which gives a short description of its contents.

## 🚀 **INSTALLATION INSTRUCTIONS**:

1. Install the gprMax-devel as you would for a normal installation, ensuring that GCC and Jupyter Notebook are installed.

```shell
$ conda update conda
$ conda install git
$ git clone --branch devel https://github.com/gprMax/gprMax.git
$ cd gprMax
$ conda env create -f conda_env.yml
$ conda activate gprMax-devel
$ cd ..
$ pip install -e gprMax
```
2. We run the install_notebook_dependencies.py file from the terminal which installs the gprMax-devel kernel in the Jupyter Notebook

```shell
$ python install_notebook_dependencies.py
```
