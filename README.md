# BM-spline

Inverse Burch-Murnaghan equation using spline interpolation.

In `pytheos` and also other apps, such as `dioptas` and `burnman`, to get volume at a given pressure, root search is used.  

However, for extremely incompressible or compressible materials, root search can fail.

In the notebook below, we set up calibration function based on spline interpolation. the function takes the following form:

V = f(P)

Therefore, it becomes very easy to calculate volume from presssure.

Ref: https://en.wikipedia.org/wiki/Spline_(mathematics)

## How to cite

S.-H. Shim (2022) Inverse Birch-Murnaghan equation with spline interpolation. Zenodo.
