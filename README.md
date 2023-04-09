# CMASRec
Code and dataset of our paper "[]" submitted to Information Sciences.

## 1. Requirements
* python 3.8.2
* pytorch 1.6.0
* numpy 1.18.1

## 2. Usage
 To train our model on MovieLens (with default hyper-parameters):
```
sh run_ml1m.sh
```
 Note that ```test_random_examples_500_XXXX.dat``` is a dict containing all negative samples for validation or test, and all baselines use the same negative samples for a fair comparison. 
 Result logs and models on each datasets are also provided.
 As for the JD and Taobao, the files are too big to upload. Please download the files on the following links:
* JDshop and taobao : [Click here.](https://drive.google.com/drive/folders/17ds021kV0_QCBXnUOGf_3scTxbT1-Tpq?usp=share_link)

