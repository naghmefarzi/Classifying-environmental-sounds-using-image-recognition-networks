# Classifying environmental sounds using image recognition networks
  -A system for automatically identifying environmental sounds like dog barking and glass breaking, which is especially useful for mobile devices.
  -Reduced the cost of development, representing environmental sounds as images, and use an image classification neural network when classi‑
fying images.
  -Evaluated classification accuracy for different image representations (Spectrogram, MFCC) of environmental sounds on available datasets, [ESC-50 and ESC-10](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/YDEPUT), using well‑known convolutional deep neural networks for image recognition (AlexNet).

## Experiment
For resampling We used the factors: 0.6, 0.9, 1.1 and . As a result, there are four times as many audio files in the expanded datasets.
We used two optimization methods (SGD & ADAM), code files namely Spectrogram_SGD and Spectrogram_ADAM and MFCC.

## Results
  -The results shown in the following table.

|              | Spectrogram Acc|   MFCC Acc    |
| :---         |     :---:      |          ---: |
| AlexNet(Adam)| 37.99          |     36.50     |
| AlexNet(SGD) | 50.55          |     49.00     |

  -The heatmap regarding using the MFCC representation and SGD optimizer is shown below:
![image](https://user-images.githubusercontent.com/78047586/194751676-27af747e-5f27-4a91-a88b-102b32864f38.png)

