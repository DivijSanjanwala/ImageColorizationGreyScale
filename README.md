# ImageColorizationGreyScale
1. Introduced Strided and Transposed Dilated Convolutions (ConvTransposeNet) instead of Upsample Layers (PoolUpsampleNet) to increase/decrease the dimensionality of tensors resulting in a 35% increase in validation accuracy to predict the color at each pixel.
2. Further introduced Skip Connections (UNet) in the ConvTransposeNet to save and reconstruct image context lost from previous layers to further increase the Validation Accuracy by 20%.
