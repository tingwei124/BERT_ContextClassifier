# BERT_ContextClassifier
Given a document, perform classification into given categories.

## Environment
Without the admin permission to the machine of the LAB, I have to use anaconda to override the CUDA version for using up-to-date PyTorch packages.
Also, the pytorch version is for RTX3090, please check the GPU on your machine and navigate to 

```shell
### step-by-step

conda create -n BERT_ContextClassifier python=3.9
conda activate BERT_ContextClassifier

conda install pandas matplotlib scikit-learn

# Torch (1.13.1+cu116) for RTX 3090
conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.6 -c pytorch -c nvidia
```

