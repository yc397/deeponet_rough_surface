The repository contains the codes of DeepONET for reconstructing 1D rough surfaces.

There are two folders corresponding to two types of boundary conditions:

Dirichlet boundary condition (TE)

Neumann boundary condition (TM)

In each case, there are 4 files:

(i) data_use_dirichlet.tar.gz is the data file in tar ball, please untar the file using 
```
tar -xzvf data_use_dirichlet.tar.gz
```

(ii) generate_data_dirichlet.ipynb is the code to generate the data, including creating rough surface and calculating the scattered field.

(iii) deeponet_surface_dirichlet.ipynb is the code of DeepONet to reconstruct surfaces, it also contains the test with respect to noisy data.

(iv) deeponet_surface_noise_dirichlet.ipynb is the code of DeepONet to reconstruct surfaces by training noisy data.
