# MSYS2-Setup
What to do after msys2 fresh install?
1. Update pacman -Syu (do it 2-3 times)
2. Install these packages
```
pacman -S axel make tree bc bison diffutils dos2unix flex m4 patch sharutils zip unrar mingw-w64-ucrt-x86_64-{vtk,itk,muparser,armadillo,cmake-gui,gcc,gcc-fortran,qt6,cli11,openvr,anari-sdk,boost,seacas,adios2,gl2ps,proj,openslide,eigen3,utf8cpp,exprtk,nlohmann-json,gtest,wxwidgets3.2,git-gui,graphviz,doxygen,ntldd,opencv,upx,octave,codeblocks,toolchain,qt-creator,indent,putty,clang,clang-tools-extra,llvm-openmp}
```
3. Python
```bash
pacman -S mingw-w64-ucrt-x86_64-{cython,pyside6} mingw-w64-ucrt-x86_64-python-{numpy,ipython,matplotlib,qtconsole,qtpy,ipykernel,scipy,scikit-image,sympy,opencv,pip,pipx}
```
