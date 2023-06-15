# DrugCompass-GCN
This is the code for the paper "DrugCompass: a Web-based system for Western and Traditional Chinese Medicine exploration".

# How to run
## 1. Train on the DDIs of Western Medicine
Use the following command to train the model on the DDIs of Western Medicine:
```
python train.py --config config_train.json
```
## 2. Inference on all the drug pairs
Use the following command to inference on all the drug pairs:
```
python inference.py --config config_infer_all.json
```

# Result
The performance of the GCN model on the DDIs of Western Medicine is as follows:
| Accuracy | Precision | Recall | ROC-AUC |
| :------: | :-------: | :----: | :-----: |
|  0.74   |   0.66   | 0.84  |  0.84  |

# Contact
If you have any questions, please contact us by email: jiannan.yang@my.cityu.edu.hk