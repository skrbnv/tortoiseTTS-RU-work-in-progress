# Tortoise TTS RU (in progress)
> :warning: **This training process is in process, done step by step and I give no promise to finalize whole process due to limited resources available. It is better if continue this on your own, without waiting.**
## Step 1: Univnet
200 epochs checkpoint available via huggingface: https://huggingface.co/my3bikaht/univnet-RU

### Training losses
![Score loss](/files/train-score.png) ![STFT loss](/files/train-stft.png) ![d-loss](/files/train-d.png) ![g-loss](/files/train-g.png)
### Validation losses
![Val mel loss](/files/val-mel.png)
### Predicted wave vs target
#### Predicted
![Predicted](/files/predicted.png)
#### Target
![Target](/files/target.png)