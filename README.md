
# 2D Planar Transformations Simulator

## Overview
This interactive simulator enables users to visualize and apply various 2D planar transformations, including:
- **Translation**
- **Euclidean**
- **Similarity**
- **Affine**
- **Projective**

The simulator is designed to help users understand how these transformations affect the geometry of a 2D plane, making it an excellent educational tool.

---

## Features
1. **Interactive GUI**: Allows users to select and apply transformations using dropdown menus and input dialogs.
2. **Transformations Supported**:
   - **Translation**: Moves the object in the X and Y directions.
   - **Euclidean**: Combines translation and rotation.
   - **Similarity**: Adds scaling to Euclidean transformations.
   - **Affine**: Applies linear transformations including shearing and scaling.
   - **Projective**: Applies non-linear transformations for perspective effects.
3. **Visualization**:
   - Original geometry and transformed geometry are displayed in the same plot for comparison.
   - Each transformation is labeled and color-coded.

---

## How to Use
1. **Run the Simulator**:
   - Save the provided MATLAB script as `planarTransformSimulator.m`.
   - Open MATLAB, navigate to the file location, and run the script by typing:
     ```matlab
     planarTransformSimulator
     ```
2. **Simulator Interface**:
   - Select a transformation from the dropdown menu.
   - Click the **Apply** button.
   - Enter the required transformation parameters (e.g., translation values, rotation angle, scaling factor) when prompted.
3. **Results**:
   - The transformed geometry is displayed alongside the original geometry on the same plot.
   - Each transformation result is labeled for easy identification.

---

## File Structure
- **planarTransformSimulator.m**: Main MATLAB script containing the simulator.
- **Dependencies**: None (only requires MATLAB).

---

## Transformation Parameters
Below is a brief explanation of the parameters for each transformation:

1. **Translation**:
   - Enter the X and Y translation values.

2. **Euclidean**:
   - Enter the rotation angle (in degrees).
   - Enter the X and Y translation values.

3. **Similarity**:
   - Enter the scaling factor.
   - Enter the rotation angle (in degrees).
   - Enter the X and Y translation values.

4. **Affine**:
   - Enter the six affine matrix elements (`a11`, `a12`, `a21`, `a22`, `tx`, `ty`).

5. **Projective**:
   - Enter all nine elements of the 3x3 projective transformation matrix.

---

## Screenshots
Include screenshots of the simulator interface and example results for transformations.

---

## Notes
- Ensure you have MATLAB installed to run the script.
- This simulator uses basic MATLAB functionality and does not require additional toolboxes.
