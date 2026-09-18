# MSYS2-Setup
What to do after msys2 fresh install?
1. Update pacman -Syu (do it 2-3 times)
2. Install these packages
```
pacman -S mingw-w64-ucrt-x86_64-{vtk,itk,muparser,armadillo,cmake-gui,gcc,gcc-fortran,qt6,cli11,openvr,anari-sdk,boost,seacas,adios2,gl2ps,proj,openslide,eigen3,utf8cpp,exprtk,nlohmann-json,gtest,wxwidgets3.2,git-gui,graphviz,doxygen}
```
3. Python
```python
pacman -S mingw-w64-ucrt-x86_64-python-{numpy,ipython,matplotlib,qtconsole,qtpy,ipykernel,scipy,scikit-image,sympy,cython}
```
