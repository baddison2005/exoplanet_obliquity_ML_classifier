# Predicting the Orbital Obliquities of Extrasolar Planets using Random Forest Classifier

Jupyter notebook containing Python code for predicting exoplanet orbital obliquities using machine learning (ML) random forest (RF) classifier models. Additionally it contains the results from these model fits.

## Description
This Jupyter notebook investigates the orbital obliquity of exoplanets by using a random forest classifier machine learning model. Here I build a model to predict an exoplanet's orbital obliquity ($|\lambda|$ or $|\psi|$) as being aligned, misaligned, or highly misaligned based on the properties of the planet itself and host star. A planet's orbit is considered aligned, misaligned, or highly misaligned when $\lambda\lt\pi/8$ (or $\lambda\lt22.5\degree$), $\pi/8\le\lambda\lt3\pi/8$ (or $22.5\degree\le\lambda\lt67.5\degree$), or $\lambda\ge3\pi/8$ (or $\lambda\ge67.5\degree$), respectively. For more information on this project, please see my other [GitHub repository](https://github.com/baddison2005/exoplanet_obliquity_ML_regression) on predicting exoplanet obliquities using random forest regression.

## Getting Started

### Dependencies

In general, these functions will require at minimum:
* Python 3.7 or newer
* Numpy
* Pandas
* Matplotlib
* Sklearn
* csv
* re
* requests
* datetime
* Astroquery
* pyvo
* Seaborn
* Bokeh
* Scipy
* tqdm

### Installing

* Download the Jupyter notebook file (orbital_obliquity_exoplanet_classifier.ipynb) and put them in an easy to access directory.
* Ensure your Python environment has the required Python libraries as noted above.

### Executing program

* In the terminal, cd to directory where you have placed the Jupyter notebook file.
* Open the Jupyter notebook file by first starting a Jupyter notebook session via the terminal command: jupyter notebook. Then open the file in the Jupyter notebook session.
* You may need to change hard coded directories in the Python code within the Jupyter notebook as appropriate.

## Help

You can email me if you are having issues getting the Jupyter notebook to work or if there are bugs in the code.

## Authors

Dr. Brett Addison  
astrobrett2005@gmail.com

## Version History

* 1.0
    * Initial Release

## License

The software is freely available at https://github.com/baddison2005/exoplanet_obliquity_ML_classifier under the GPL-3.0 license.
