## 3D Visualization Toolbox

This toolbox contains the `plot_3D_model.py` package that uses the PyVista library to show the 3D geometry of the model.
This package contains the `visualize_vti_output` function which is used to visualize the 3D geometry. 

The dependencies for this package include *PyVista* and the *gprMax-devel kernel* within Jupyter notebook which can be installed as already described, i.e by running the `install_notebook_dependencies.py` script. 

Activating the `gprMax-devel` kernel in the Jupyter Notebook environment and other installation instructions are present in the main `README`.

To use this in a Jupyter cell, follow these steps:

1. Install the PyVista library by running the following command in a code cell:
   ```python
   !pip install pyvista -qq
   ```
2. Keep the plot_3D_model.py file in the same directory as your Jupyter Notebook. Or do comparative imports like:

    `from visualization_toolbox.plot_3D_model import visualize_vti_output`

3. In your Jupyter Notebook, import the function from the plot_3D_model.py file and use it to visualize the 3D geometry of the      model.

## The `visualize_vti_model` Function

The `visualize_vti_model` function takes arguments in the following way:

```python

visualize_vti_output(filename, orientation = 'xy', opacity = 0.4, backend = 'static'):

```
**Arguments:** <br>
1. *filename* : string of filename (including path) of the geometry view file. <br>
   eg: `cylinder_half_space.vti`
2. *orientation* : string in which plane the 3D output is to be shown. <br>
   eg: `xy`, `yz`, `zx`
3. *opacity* : float point value to determine the transparency of the background. <br>
   eg : `0.5`
4. *backend* : string for the 3D plot to be static or dynamic.
<br>

## Example Code 

```python

    from plot_3D_model import visualize_3D_model

    # Call the function to visualize the 3D model
    visualize_3D_model(arguments)  


```

An example of a simple 3D visualization is shown using the `simplebscan.vti` file in the `test_3D_output_notebook.ipynb` file