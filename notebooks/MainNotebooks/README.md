# README file for the SLSIM/Notebooks/MainNotebooks

This README provides a quick summary about what each notebooks is performing. 

# Notebook 01:

- [slsim_single_lens_simulation.ipynb](slsim_single_lens_simulation.ipynb)::  This nb shows 4 basic examples of Strong Lensing cases of single source in which 4 SL images from the original source are generated. It simulates through SLSIM the Rubin-LSST image pixels. Those telescope images are either coadded for static sources or comes as snapshot series at tifferent time sampling for transcients sources. 
A a generic elliptic static source, a supernovae, and a quasar or transcient generic source. In each example, the deflector is specified by lens intensity profile, its light and mass tangential and cross ellipticities ($e_1$,$e_2$) and the Einstein radius $\theta_E$. 
The detection is specified by the psf kernel, the pixel transform matrix (pixel size in arcsec) and the sky background in the different bands (g,r,i) in the telescope pixels (not sure of the units there). 
      
  - example 1 : a static source : the source has a static sersic ellipse intensity profile (EPL_SERSIC) and the deflector has ellipticities ($e_1$,$e_2$)  and the Einstein radius $\theta_E$. Note 3 telescope images in band g,r, i are simulated from which a RGB composite image is shown.

  - example 2: a SN source : the source has one light-curve (provided by slsim) and snpashot of the telescope images in band i are shown at different times sampled. The time delayed light curves of 4 images is shown. Note the delay is of the order of a few days.

  - example 3: a Quasar source : the source has one light-curve (provided by slsim) and snpashot of the telescope images in the band i are shown at different times sampled. The time delayed light curves of 4 images is shown. Note the delay is of the order of months or more.
 
  - example 4 : A generic transcient source with a light-curve given inside a notebook.  The snpashot images at different times sampled. The time delayed light curves of 4 images is shown. 
   
  
# Notebooks 02 and 03:

- [galaxy_galaxy_lensing_tutorial.ipynb](galaxy_galaxy_lensing_tutorial.ipynb):: do this and that

- 