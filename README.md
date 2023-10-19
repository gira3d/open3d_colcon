# Open3D Colcon
This is a colcon package that adds our modified version of Open3D as a git submodule and sets up the desired
configuration parameters in CMakeLists.txt.

# CHANGELOG

## New in 0.0.1
- Added a python wrapper function to compute closest point cloud distance along with indices of the closest points.
- Build system fixes to use specific Eigen and Pybind11 versions.
- Disable the cached memory manager by default.
- Enable exporting pybind11 headers to use in custom bindings.
