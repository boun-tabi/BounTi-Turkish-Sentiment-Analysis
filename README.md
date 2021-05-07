This repository includes training scripts, the finetuned model, and the dataset for BOUN Turkish Sentiment Analysis.

## Dataset
You can find the dataset in the data folder with the training, validation, and test splits.

Due to Twitter copyright, we cannot release the full text of the tweets. We share the tweet IDs, and the full text can be downloaded throught official Twitter API.

|          | Training | Validation | Test |
|----------|:--------:|:----------:|:----:|
| Positive | 1691     |     188    |  469 |
| Neutral  | 3034     |     338    | 843  |
| Negative | 1008     |     113    | 280  |
| Total    | 5733     |     639    | 1592 |

## Model
BERTurk model: [Download (1.3 gb)](https://tabilab.cmpe.boun.edu.tr/models/berturk_boun_sentiment_analysis.zip)

The scores of the finetuned model with BERTurk:
|             |  Accuracy | Precision | Recall |   F1  |
|-------------|:---------:|:---------:|:------:|:-----:|
| Validation  |   0.745   |   0.706   |  0.730 | 0.715 |
| Test        |   0.723   |   0.692   |  0.729 | 0.701 |


## Citation
You can cite the following paper if you use our work:
```
@INPROCEEDINGS{BounTi,
  author={Köksal, Abdullatif and Özgür, Arzucan},
  booktitle={2021 29th Signal Processing and Communications Applications Conference (SIU)}, 
  title={Twitter Dataset and Evaluation of Transformers for Turkish Sentiment Analysis}, 
  year={2021},
  volume={},
  number={}
  }
```
---
