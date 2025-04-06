# beyondThePixelCustom
A customization of the original beyondthepixel paper for the purpose of LDR to HDR conversion

Added pretrained weights Luminance_LDR to checkpoints folder in Learning Tasks. Resized ldr images to (128, 64) for conversion to ldr using size_conv.py. Edited the config file in Luminance_LDR to change the path of the dataroot to /Learning Tasks/my_imgs and solid map to sa_open.exr in the same folder.
