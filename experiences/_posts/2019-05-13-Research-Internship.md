---
layout: post
title: Research Internship
abstract:  R&D Project under Dr. Sreejith Padinhatteeri, Inter-University Centre for Astronomy and Astrophysics, Pune. 
---
- Technology Stack – Zemax OpticStudio, ZOS-API, Python: Numpy, Scipy, Scikit-learn
- The project aimed to develop a Machine Learning based Optical fine Alignment tool. The tool aims to model the variations in the Zernike Coefficients due to the misalignment of the optical components of the telescope, and then apply various Machine Learning algorithms to accurately predict the exact component having the misalignment, and the actual misalignment.
- The project consists of two components: Generation of Dataset and Application of various Machine Learning algorithms.
- The datasets consist of Standard Zernike Coefficients (37 coefficients) generated at the image plane, at all possible perturbations under the optical and mechanical tolerances defined previously, created using ZOS-API for Python.
- The optical diagram of the system has been previously created using the Zemax OpticStudio, and used as a base to generate various perturbations using the API.
- The dataset created, was preprocessed and standardized.
- A Multi-class Random Forest Classifier was used to predict the exact component of the mis-alignment, and every class had its own Multi-Output Decision Tree Regressor, so as to predict the actual misalignment in all possible parameters.
- This tool is proposed to be used in the Solar Ultraviolet Imaging Telescope (SUIT), one of the payloads of the Aditya-L1 mission of Indian Space Research Organization (ISRO) 
