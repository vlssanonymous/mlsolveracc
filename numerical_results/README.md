# A Machine Learning Acceleration for Nonlinear PDE Solvers

- **featureselection**: Numerical experiments for the feature selection.
- **modelselection**: Numerical experiments for the model selection.

### Numerical results

Inside **featureselection** and **modelselection** there are four folders:

- 2D_2layered: two-dimensional layered reservoir used for training.
- 2D_4quadrants: two-dimensional heterogeneous reservoir with permeability varying in four quadrants.
- 3D_channels: realistic three-dimensional channelized reservoir.
- 3D_faulted:  realistic three-dimensional faulted reservoir.

From inside this folders execute *non_linear_iterations_ximproved.ipynb*: 

Inside the notebook
```
Cell->Run All 
```

or using the command line:
```
$ jupyter nbconvert --to notebook --execute <notebookname>.ipynb
```


