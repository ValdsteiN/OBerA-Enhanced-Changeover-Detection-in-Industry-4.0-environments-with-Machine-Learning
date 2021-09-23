# OBerA-Enhanced-Changeover-Detection-in-Industry-4.0-environments-with-Machine-Learning

A repository with ML models of the OBerA project which goal is to optimize changeover times in manufacturing using a combination of sensors, Industry 4.0 and Machine learning approaches. The project is carried out by the University of Applied Sciences Würzburg-Schweinfurt in cooperation with Pabst GmbH.

This repository belongs to the article ["Enhanced Changeover Detection in Industry 4.0 Environments with Machine Learning"](https://www.mdpi.com/1424-8220/21/17/5896/htm). Also, the link in text form: <https://www.mdpi.com/1424-8220/21/17/5896/htm>

<img src="https://raw.githubusercontent.com/ValdsteiN/OBerA-Enhanced-Changeover-Detection-in-Industry-4.0-environments-with-Machine-Learning/main/qr-code.png" alt="MDPI QR code" width=250px />

### Erratum

Currently, the AUC score for the Neural Network in the article found in [figure 7](https://www.mdpi.com/sensors/sensors-21-05896/article_deploy/html/images/sensors-21-05896-g007.png) is 94.21%.

However, you might notice that in the notebook the AUC score for Neural Network is 86.46%.

The AUC score in the notebook is the *correct* one. The discrepancy was caused by a rounding error and we apologize for that. We are doing our best to also fix it in the article. Nevertheless, this error by no means impacts the validity of the article, as even with the higher AUC score the Neural Network did not make it past our evaluation threshold.
