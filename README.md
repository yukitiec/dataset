# dataset
## dataset for img classification model
### mkDataset_ViT_spatterFrame_estimation.jpynb
#### dataset for MAE(Masked Autoencoder) 
- concatenate 9 images and put a frame, in whose frame spatter is yielded
### mkDataset_Vit.jpynb
#### dataset for ViT(Vision Transformer) 
- concatenate 9 images and include spatter and non-spatter data
#### *Caution: spatter frame isn't included except bottom left frame. This is because we wanna predict spatter occurence
