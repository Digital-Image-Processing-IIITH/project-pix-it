# PIX-IT

Team PIX-IT has worked on the Fast Bilateral-Space Stereo for Synthetic Defocus paper by researchers at Google.


##  Requirements
> This project expects the following libraries to be present on the users system along with Python3

> These libraries can be installed via `pip`

- `Jupyter`: tools for working with code, text in one place
- `OpenCV`: a library of programming functions mainly aimed at real-time computer vision
- `Numpy`: for dealing with large, multi-dimensional arrays and matrices
- `MatplotLib`: a plotting library 
- `SciPy`: for scientific computing
- `PyLab`: an interface to Matplotlib (Generally gets installed with MatPlotLib by default)

## To run the code!
  - Please open the 'src' folder
  - The 'BilateralSolver.ipynb' is our fully functional notebook. 
    - It includes all the modules, classes
    - It runs all the tests
  - Simply run all cells of 'BilateralSolver.ipynb' in order.

## Documentation of the code
  - [Link]("./references/documentation_html/index.html") to the documentation.
  - Documentation created using Sphinx documentation generator.

## Sources for stereo images
- https://vision.middlebury.edu/stereo/data/
- https://vision.deis.unibo.it/fede/ds-stereo-lab.html

## Repository Structure
- `documents`
  - `PIX-IT-Final.pdf`: the PDF version of final presentation. (Recommended for presentation!) 
  - `PIX-IT-Final.pptx`
  - `PIX-IT_mideval_presentation.pdf`
  - `PIX-IT_mideval_presentation.pptx`
  - 
- `images`: contains images used in code (4 pair of stereo images)
- `references`: contains reference papers
  - `documentation_html`: open `index.html` file to run the documentation on the browser
- `src`
  - `own`: [ARCHIVE] contains rough notebooks where we tried and tested different approaches
  - `BilateralStereo.ipynb`: Main Notebook. Run this!
- `readme.md`: [This File]
- `proposal.md`: project proposal
