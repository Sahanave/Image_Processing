EE569 Sahana Venkatesh #1 
# Date: 5 February 2017
# Name:     Sahana Venkatesh 
# ID:       6643244225
# email:  sahanave@usc.edu

Compiler:g++ 
IDE:Codeblocks
OS:macOS Sierra 10.12.2 

Instructions:

•	Make sure the image are in the same folder as the Programs.
•	Please change the arguments in makefile if new test images are used.
•	Input and output images are in .raw format.
•	To compile and run the program just type: make program name
•	To help,please have a look at the below writeup which is intended to guide one regarding how to pass arguments and what are the output images.
•	Mostly the second argument (passed next to the input image) is the name of the output image.
Problem 1:1
)a)mirroring-mirror.cpp
Pass the in following format as argument 
./mirror dog.raw output_image.raw [BytesPerPixel=3][Height=300][Width=300]
b)resize:-resize.cpp
make program_name dog.raw output_image.raw [BytesPerPixel = 3] [Initial Size=300][New size=400]
c)image composting-imagecomposting.cpp
make program_name dog.raw beach.raw output_image.raw
d)to run cmyk-cmyk.cpp
program_name parrot.raw output_cyan_image.raw output_magenta_image.raw output_yellow_image.raw
e)To run HSL-hsl.cpp
program_name cat.raw hue.raw satuaration.raw luminance.raw
f)for Sepia-sepia.cpp
make program name beach.raw intermidiate_image.raw output_image.raw
g)for blending-blending.cpp
make program_name top_layer.raw bottom_layer.raw output_image.raw

Problem 1.2
a.1)for Histogram enhancement method:-histogram_enhancemt.cpp
make program name input image.raw output_image.raw [H_min_of first cluster=0][H_max of first cluster=68] [H_min_2nd cluster=190] [H_max of 2nd cluster=255]
This is incase your image has two clusters. If it has one cluster enter max and min pixel intensity value.
a.2)For cumulative method based histogram equalization technique:histogram_equalization.cpp
make  program name tulip_bright.raw output_image.raw 

2)a)To run Histogram enhancement method for three channels- histogram_enhancemt(2_a)method.cpp
b)To run Bucket filling for three channels(Method B)- histogram_equalization(2_b)method.cpp
program name input_name.raw output.raw   
c)Histogram matching-histmatch.cpp
./main forest_1.raw output.raw
3)MEAN AND MEDIAN FILTER-mean_median.cpp
Program name pepper_noisy.raw output_a.raw windowsize
4)NLM-nlm.cpp
Program name pepper_noisy.raw output_a.raw windowsize



