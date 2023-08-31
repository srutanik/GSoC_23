## 3D Visualization Toolbox

This toolbox contains the `plot_3D_model.py` package that uses the PyVista library to show the 3D geometry of the model.

It can be used after activating the `gprMax-devel` kernel in the Jupyter Notebook environment. Instructions for that are present in the `README`.

To use this in a Jupyter cell, follow these steps:

1. Install the PyVista library by running the following command in a code cell:
   ```python
   !pip install pyvista -qq
   ```
2. Keep the plot_3D_model.py file in the same directory as your Jupyter Notebook. Or do comparative imports like:

    `from visualization_toolbox.plot_3D_model import     visualize_3D_model`

3. In your Jupyter Notebook, import the function from the plot_3D_model.py file and use it to visualize the 3D geometry of the      model.

## Example Code 

```python

    from plot_3D_model import visualize_3D_model

    # Call the function to visualize the 3D model
    visualize_3D_model(arguments)  


```

An example of a simple 3D visualization is shown using the `simplebscan.vti` file in the `test_3D_output_notebook.ipynb` file