## segmentation_autofluorescence
Methods to segment autofluorescence from NADH/FAD images

## test image done manually
* polygon- fast/single cell data
![alt text](https://github.com/JenuC/segmentation_autofluorescence/blob/master/manual_segmentation_result.png)
* threshold- fast/ grouped data
* 
![alt text](https://github.com/JenuC/segmentation_autofluorescence/blob/master/manual_segmentation_threshold.PNG)
* 
* threshold + selection slow/single cell data
![alt text](https://github.com/JenuC/segmentation_autofluorescence/blob/master/manual_segmentation_threshold_selection.PNG)
* 
Free hand drawn shapes or polygon shapes(as seen above) are commonly used to separate the cells in such images. There is a need for a better cell-segmentation method. 
## Options
I have been mitigating this problem using two methods
* get spare cell concentration biologically
* using ImageJ (combination of wand_tool, selection_tool and thresholding)

I wonder if there is already an intelligent segmentation method available to solve this problem?

