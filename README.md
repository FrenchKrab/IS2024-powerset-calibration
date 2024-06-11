# On the calibration of powerset speaker diarization models

[Alexis Plaquet](https://frenchkrab.github.io/) and [Hervé Bredin](https://herve.niderb.fr)  
Proc. InterSpeech 2024.

> End-to-end neural diarization models have usually relied on a multilabel-classification formulation of the speaker diarization problem. Recently, we proposed a powerset multiclass formulation that has beaten the state-of-the-art on multiple datasets. In this paper, we propose to study the calibration of a powerset speaker diarization model, and explore some of its uses.
> We study the calibration in-domain, as well as out-of-domain, and explore the data in low-confidence regions. The reliability of model confidence is then tested in practice: we use the confidence of the pretrained model to selectively create training and validation subsets out of unannotated data, and compare this to random selection.
> We find that top-label confidence can be used to reliably predict high-error regions.  Moreover, training on low-confidence regions provides a better calibrated model, and validating on low-confidence regions can be more annotation-efficient than random regions.

[📄 Read the paper (ISCA)](https://www.isca-speech.org/archive/interspeech_2024/plaquet24_interspeech.html)

[🌐 Browse the companion website](https://frenchkrab.github.io/IS2024-powerset-calibration/)

[🐍 Install the python package](https://github.com/FrenchKrab/powerset_calibration/)

## Citations

To be added.
