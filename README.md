# Classifying the Source Radius from Microlensing Light Curves using Neural Networks

Practical work (TP4b) with Laboratory of Astrophysics, EPFL, Lausanne.

With the dawn of all-sky surveys and time domain astronomy, which are expected to discover thousands of lensed quasars in the coming decade, deep learning provides one of the most feasible techniques to analyze microlensed light-curves. This project aims to classify quasar source sizes into ten categories using simulated microlensing light curves, which closely mimic the COSMOGRAIL light curves in terms of photometric noise, seasonal visibility and duration of the monitoring campaign. This classification is brought about by using three deep learning algorithms: a Convolutional Neural Network (CNN), and two Residual Neural Networks (ResNet-7 and ResNet-18). It was found that the ResNets outperformed the CNN by > 10%, and the models were able to best classify to light-curves when the season gaps were fitted using linearly interpolation, as opposed to the curves fitted using Gaussian processes regression. Using linearly interpolated light curves, ResNet-7 achieved 63.4% accuracy, while ResNet-18 achieved 66.1% accuracy.

Refer to the TP4b report in this repo for further details. 
