# English-to-French translator based on Transformer implementation.

# Environment

python==3.11.10  
torch==2.5.1  
torchvision==0.20.0  
torchaudio==2.5.0  
datasets==3.0.2  
tokenizers==0.20.1  
torchmetrics==1.5.1  
tensorboard==2.18.0  
altair==5.4.1  

# Operation

Loaded dataset is sourced from Hugging Face, with English and French as the languages used.

Training objective is **English-to-French** translation.

Following command is used for training the weights.

```
python .\train.py
```

Once the weights are obtained, use the command below for translation.

```
python .\translate.py
```

Use the model to inference.

```
inference.ipynb
```

Visualize the weights.

```
attention_visual.ipynb
```
