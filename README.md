# Omni-supervised Shadow Detection with Vision Foundation Model
by Zeheng Qian, Wen Wu, Xian-Tao Wu, and Xiao-Diao Chen

#### News: In 2023.11.26, We release the unsorted code for other researchers. The sorted code and datasets will be released after.

## Highlights
🏆 Low GPU requirements. (one 3090 with 24G GPU memory is enough)\
🏆 Flexible labeling manner for shadow images


## Training
Once you have the data ready, you can start training the model.
```
python train.py --modelname ShadowSAM --task <your dataset config name>
```
## Testing
```
python test.py --modelname ShadowSAM --task <your dataset config name>
```
