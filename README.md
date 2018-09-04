# mw_data_aug
This code snippet use imgaug(https://github.com/aleju/imgaug) library to augment the given input images and convert them in the same directory structure as input was.

## Example:
If the given input images that needs needs to be augmentaed, are in following directory structure.
```
dir/images/dog/
          /cat/
          /fish/
          /ball/ 
          ...
 ```         
the output result will also be in the same directory structure as:
```
mw_output/images/dog/
                /cat/
                /fish/
                /ball/
                ...
 ```
 ## Customization 
 The code can be customized for specific needs of augmentation. Please feel free to makes changes and add more options. 
 
 ## Future work
 Presently the code runs on CPU, this needs GPU acceleration. 
