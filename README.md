# Scenergy Scene Text Recognition with Conditional Random Fields

This work was done as part of project for the course Probabilistic Graphical Models. The work takes inspirationfrom the paper "Top-Down and Bottom-up Cues for Scene Text Recognition" by Anand Mishra et al. (CVPR 2015). Here, we try to extend the character-level idea presented in the paper to word-level scene text recognition for small length sequences.

The model is as given below:

![Architecture](https://github.com/surabhisnath/Scenergy-Scene-Text-Recognition-with-CRFs/blob/master/model.png)

The following models designs were compared:
- Only DL model
- DL model with Linear CRF
- DL model with Nonlinear fully-connected CRF
- DL model with Nonlinear fully-connected CRF and Positional Weighting

Refer to Scenergy_Slides.pdf and Scenergy_Report.pdf for further details of the work and the obtained results.

Project done by:

- Surabhi S. Nath (surabhi16271@iiitd.ac.in)
- Pranav Goyal (pranav17078@iiitd.ac.in)
