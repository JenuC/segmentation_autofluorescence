## segmentation_autofluorescence
Methods to segment autofluorescence from NADH/FAD images

## test image done manually
Free hand drawn shapes or polygon shapes(as seen above) are commonly used to separate the cells in such images. There is a need for a better cell-segmentation method. 
* polygon- fast/single cell data
* threshold- fast/ grouped data
* threshold + selection slow/single cell data
output of such markings looks like these:
![alt text](https://github.com/JenuC/segmentation_autofluorescence/blob/master/manual_segmentation_result.png)
![alt text](https://github.com/JenuC/segmentation_autofluorescence/blob/master/manual_segmentation_threshold.PNG)
![alt text](https://github.com/JenuC/segmentation_autofluorescence/blob/master/manual_segmentation_threshold_selection.PNG)


## Options
I have been mitigating this cell-separation problem using two methods
* get spare cell concentration biologically
* using ImageJ (combination of wand_tool, selection_tool and thresholding as shown above)
I wonder if there is already an intelligent segmentation method available to solve this problem?
