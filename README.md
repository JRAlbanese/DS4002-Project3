# DS4002-Project3
Jason Albanese, Brian Xiao, Elaine Shagdarjav
# Section 1: Software and Platform
* We extracted our image data from GitHub. It contains 2,000 images with 5,932 bounding boxes with four possible categories: "Children Without Disability", "Elderly without Disability", "With Disability", and "Non-Vulnerable". We created a 20/80 train/validation split among these resized images.

* We will be employing and comparping MobileNetV2, InceptionV3, and EfficientNetV2M on our pedestration image data.

* Windows and Mac were used to run software on Google CoLab. These packages will be necessary to run:
	* pandas
	* tensorflow
	* numpy
	* pycocotools
	* opencv-python-headless
	* cv2
	* sklearn
	* matplotlib
	* scipy
# Section 2: Documentation Map
## Annotations Folder
* combined_annotations.coco.csv
* combined_annotations.coco.json
## Scripts Folder
* initial.ipynb
* annotations_and_image_initialization.ipynb
* Inception_Analysis.ipynb
* MobileNet_Analysis.ipynb 
* ResNet_Analysis_Extended.ipynb
## Image_Data Folder
* DS 4002 Project 3 raw image data (contains jpg files of all images)
## Output Folder
* annotations_boxplot.png
* annotations_histogram.png
* categories_piechart.png
* image_sizes_histogram.png
# Section 3: Instructions for Reproducing Results
1. Clone this repository
2. Download the following libraries/packages: (This can be done through the terminal with the following syntax: pip install <library>)
	* pandas
	* tensorflow
	* numpy
	* pycocotools
	* opencv-python-headless
	* cv2
	* sklearn
	* matplotlib
	* scipy
3. Run *initial.ipynb*
4. Run *annotations_and_image_initialization.ipynb*
5. **In Google CoLab**, run *Inception_Analysis.ipynb*, *MobileNet_Analysis.ipynb*,and *ResNet_Analysis_Extended.ipynb*


devvansh1997. (2022). BGVP/Dataset at main · devvansh1997/BGVP. GitHub. 
https://github.com/devvansh1997/BGVP/tree/main/Dataset

Sharma, D., Hade, T., & Tian, Q. (2022). Comparison of deep object detectors on a new vulnerable pedestrian dataset. arXiv. https://doi.org/10.48550/arXiv.2212.06218 

Computer vision with TensorFlow. (2024). TensorFlow. 	
https://www.tensorflow.org/tutorials/images?hl=en

Team, K. (n.d.). Keras documentation: Image classification from scratch. Keras.io. 
https://keras.io/examples/vision/image_classification_from_scratch/
