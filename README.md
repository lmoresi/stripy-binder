# Stripy - binder wrapper for python package

A Python interface to TRIPACK and STRIPACK Fortran code for (constrained) triangulation in Cartesian coordinates and on a sphere. Stripy is an object-oriented package and includes routines from SRFPACK and SSRFPACK for interpolation (nearest neighbor, linear and hermite cubic) and to evaluate derivatives (Renka 1996a,b and 1997a,b).

`stripy` is bundled with `litho1pt0` which is a python interface to the _crust 1.0_ dataset and the lithospheric part of the _litho 1.0_ dataset (Laske et al, 2013 and Pasyanos et al, 2014) which both requires and demonstrates the triangulation / searching and interpolation on the sphere that is provided by `stripy`.

---

![Examples](https://github.com/University-of-Melbourne-Geodynamics/stripy/blob/master/Notebooks/Images/Examples.png?raw=true)

_Sample images created with `stripy` illustrating the meshing capability, the ability to refine meshes to match criteria such as data density, and the ability to create distance-weighted averages to meshes and continuous interpolating functions_

Stripy is available through pypi: [https://pypi.org/project/stripy/](https://pypi.org/project/stripy/) as well as in
docker form. This repository repackages the standard docker to work better with [binder](mybinder.org).
