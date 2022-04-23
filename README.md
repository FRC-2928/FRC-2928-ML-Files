# FRC-2928-ML-Training-Files
This repository contains intermediate files required to train a deep learning model.  The purpose is to be able to share these files with other FRC teams.

The following files are included:
- `Rapid-React-Ball-Dataset` A set of annotated jpeg files of the FRC 2022 competition Rapid-React balls.  The annotations are in COCO JSON format and can be used to train your own model.  This dataset contains about 1040 annotated images.

- `rapid-react_best.weights`  This is a trained model on the FRC 2022 competition Rapid-React balls.  This can be converted into a Tensorflow Lite model or other models suitable for your deployment target.

- `OpenVINO-IR_Files` *Intermediate Representation* *IR* files used to deploy to a device using the OpenVINO Toolkit.