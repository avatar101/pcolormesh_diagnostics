# pcolormesh_diagnostics
Dig deeper into the interpolation difference between various plotting functions

`pcolormesh` interprets data as edge of the data. Problem can arise if the data is meant for the centeroid of the grid points.
In such a case, manual shift of the data is needed as shown in this notebook
