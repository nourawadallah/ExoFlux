# ExoFlux

Status: Under Development

ExoFlux is an exoplanet detection pipeline designed to analyze stellar light curves for planetary transits. The project utilizes deep learning to identify the subtle dipping of a star's brightness caused by an orbiting planet passing in front of it. The project is currently active and in an ongoing development phase.

## Dataset

The project utilises the Kepler Exoplanet Detection Dataset from Kaggle to analyse stellar light curves for planetary transits:
https://www.kaggle.com/datasets/ronaldkroening/exoplanet-detection-dataset

## Current Performance

The latest iteration of the 1D-CNN model has achieved the following metrics on the evaluation dataset:

* Accuracy : 0.8744
* ROC-AUC : 0.9193
* PR-AUC : 0.9438

> Current development is focused on optimising the architecture with the goal of reaching ~90% accuracy.

Note: As this project is actively being developed, all metrics and implementations are subject to change.
