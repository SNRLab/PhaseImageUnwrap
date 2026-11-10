# PhaseImageUnwrap

A 3D Slicer module for unwrapping MRI phase images. Select a phase image and
click **Unwrap Image**: the module creates an unwrapped phase image
(`<name>-phaseUnwrap`) using scikit-image's `unwrap_phase`, and its gradient
magnitude image (`<name>-phaseGrad`). Click **Install Dependencies** first to
install scikit-image into 3D Slicer's Python.

## License

Distributed under the 3D Slicer license, a BSD-style license. See
[License.txt](License.txt).
