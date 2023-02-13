# cervical-spine-fracture-prediction

This notebook predics Cervical Spine Fractures from Computed Tomography (CT) scans.

**Dataset**
The dataset  is made up of roughly 3000 CT studies (https://www.kaggle.com/competitions/rsna-2022-cervical-spine-fracture-detection/overview/acknowledgements).

We need to predict the probability of fracture for each of the seven cervical vertebrae labeled C1, C2, C3, C4, C5, C6 and C7 as well as an overall probability of any fractures in the cervical spine. This means there will be 8 rows per image id in the submission file. Note that fractures in the skull base, thoracic spine, ribs, and clavicles are ignored.
    
The metric to evaluate performance is a weighted multi-label logarithmic loss (averaged across all patients).
