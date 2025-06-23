# Mouse Sleep Staging Validation dataset (MSSV)

This dataset contains EEG recordings with sleep scores from 92 healthy mice. The recordings and sleep scores were collected from five different labs:

- Department of Biomedical and Neuromotor Sciences, Università di Bologna.
- Center for Translational Neuroscience, University of Copenhagen, Denmark.
- Department of Neuroscience, University of Copenhagen, Denmark.
- Zentrum für Experimentelle Neurologie, Department of Neurology, Inselspital University Hospital Bern, Bern, Switzerland.
- Lyon Neuroscience Research Center, Lyon, France.


## Overview

-   It contains EEG data from healthy mice in both dark and light phases. 

-   All recordings contain at least one EEG and one EMG channel. The number of EEG channels available varies between labs (see labs.tsv).

-   The dataset is formatted according to the Brain Imaging Data Structure. See the 'dataset_description.json' file for the specific BIDS version used. The recordings are stored in .EDF format.

-   This dataset has been used and is fully described in https://doi.org/10.1093/sleepadvances/zpaf025.

## Methods

-   There are 92 healthy mice from 5 different labs. Each mouse is scored by a single sleep expert. See participants.tsv to see what lab each mouse belongs to. 

-   All recordings have been downsampled to 128Hz and have SI units (volts). The epoch length is 4 seconds.

## Contact

For questions regarding this dataset, contact Birgitte Rahbek Kornum, kornum@sund.ku.dk