# Title:
# Automatic crack classification by exploiting statistical event descriptors for Deep Learning

# Authors:
# Giulio Siracusano, Francesca Garescì, Giovanni Finocchio, Riccardo Tomasello, Francesco Lamonaca, 
# Carmelo Scuro, , Mario Carpentieri, Massimo Chiappini and Aurelio La Corte
# email: giuliosiracusano@gmail.com

# Description
# Zip Archive is composed of 3 files:
1. Training_dataset_15000AE_1000_samples.mat
2. Testing_dataset_1650AE_1000_samples.mat
3. README.md (this file)

# Legend
# Training Dataset (Matlab Format)
# Training_dataset_15000AE_1000_samples.mat

XTrain is in the format of 15000x1000 samples
       there are 15000 events (5000 are tensile, 5000 shear and 5000 mixed-events)
       each acoustic event is composed of 1000 time samples
YTrain is the categorical array in the format of 15000x1
       AE events are classified according to the following type: 
       '1' = Tensile Mode
       '2' = Shear Mode
       '3' = Mixed-Mode
freq   is the vector of frequencies related to the given sampling frequency. It is composed of 501 elem(s)
time   is the time vector (sampling frequency has been reduced to 500kHz to save space). It is composed of 1000 elem(s)

# Testing Dataset (Matlab Format)
# Testing_dataset_1650AE_1000_samples.mat
XTest is in the format of 1650x1000 samples
       there are 1650 total events for testing (550 are tensile, 550 shear and 550 mixed-events)
       each acoustic event is composed of 1000 time samples
YTest is the categorical array in the format of 1650x1
       AE events are classified according to the following type: 
       '1' = Tensile Mode
       '2' = Shear Mode
       '3' = Mixed-Mode
freq   is the vector of frequencies related to the given sampling frequency. It is composed of 501 elem(s)
time   is the time vector (sampling frequency has been reduced to 500kHz to save space). It is composed of 1000 elem(s)

# Last Revision
# 14-Dec-2021			