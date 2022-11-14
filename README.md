# Swahili Audio Classification (Zindi Challenge)

[Link to Zindi Challenge Page](https://zindi.africa/competitions/swahili-audio-classification)

The goal of the Swahili Audio Classification challenge is to classify 12 swahili words recorded in wav-files. The words and english translations are shown below.

| Swahili |	English |
| --- | --- |
| ndio |	yes |
| hapana |	no |
| moja |	one |
| mbili |	two |
| tatu |	three |
| nne |	four |
| tano |	five |
| sita |	six |
| saba |	seven |
| nane |	eight |
| tisa |	nine |
| kumi |	ten |

A short introduction to the data is shown in the notebook "EDA.ipynb". 'Model_torchaudio.ipynb' contains the pytorch model including preprocessing, training and testing the model. A pretrained resnet18 model is used. This model can be either trained with normal spectrograms or mel spectrograms as preprocessing. Preprocessing using the mel spectrogram scored 0.168465426 and reached **rank 16** of 40.
