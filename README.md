# implemented-time-series
# Atlas database:

We present some time series under study, obtained from the Atlas database (Frauscher, 2018a, 2018b; von Ellenrieder,2020). This database includes iEEG recordings made in various regions of the human brain; however, in this work we focus exclusively on measurements from the medial frontal cortex. The processed data are available in the repository under the file named "signals_mfc_wake.mat".

## Details:

- Average duration per signal:** 60 seconds
- Sampling rate:** 200 Hz  
- **File format:** `.mat`.  



## Bibliography: 

Frauscher, B., Von Ellenrieder, N., Zelmann, R., Doležalová, I., Minotti, L., Olivier, A., ... & Gotman, J. (2018a). Atlas of the normal intracranial electroencephalogram: neurophysiological awake activity in different cortical areas. Brain, 141(4), 1130-1144.

Frauscher, B., von Ellenrieder, N., Zelmann, R., Rogers, C., Nguyen, D. K., Kahane, P., ... & Gotman, J. (2018b). High‐frequency oscillations in the normal human brain. Annals of neurology, 84(3), 374-385.

von Ellenrieder, N., Gotman, J., Zelmann, R., Rogers, C., Nguyen, D. K., Kahane, P., ... & Frauscher, B. (2020). How the human brain sleeps: direct cortical recordings of normal brain activity. Annals of Neurology, 87(2), 289-301.

# Time series from simulations of different stocks:

Time series of simulations performed with the FS-RS neuronal population are attached. The simulation was carried out over a period of 60,000 milliseconds, recording the temporal evolution of the membrane potential of each neuron in the network. From these recordings, a global variable called LFP (Local Field Potential) was constructed, designed to emulate membrane potential measurements obtained from intracranial EEG (iEEG) recordings. This variable was calculated as the sum of the membrane potentials of all neurons in the network at each time instant. The time series are available in the repository in the file named “RS-FS.mat”.
To implement the time series analysis, it is necessary to first download all the files and extract their contents.
