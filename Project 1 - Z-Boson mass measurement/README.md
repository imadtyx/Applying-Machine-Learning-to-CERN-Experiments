In this project, we want to analyse the mass spectrum of particle decaying into muon-antimuon (dimuon) pairs and figure out the mass of Z boson. Of course, the mass of Z boson can be looked up at the PDG, but it is much more fun in computing it ourselves!

If the histogram of mass distribution is plotted, a mixture of parametrised signal and background distributions can be fit into the shape of the plotted histogram. The signal would correspond to a peak-like shape. For ease we gauge the background as a flat level. The parameters of the mixture will be the mass of Z boson and different measurements of the criticalness and vulnerability of the estimation.

To find the mass, we need to fit the mixture of 1) Gaussian distribution to obtain parameters- centre of the Gaussian, it's peak height, and deviation and 2) Flat distribution using scikit-optimise toolkit as it is described in the notebook here to calculate level of the background.
