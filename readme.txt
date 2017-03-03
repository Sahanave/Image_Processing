EE569 Sahana Venkatesh #1 
# Date: 26 February 2017
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
•	To help,please have a look at the below writeup which is intended to guide one 
regarding how to pass arguments and what are the output images.

Problem 1
Geometrical Image modification
linear(prob1).cpp -linear warping 
Input image name is an input inside(coded) the program(cup2.raw is current input)
output image is set in the program (current output is cup_2_linear.raw)
make linear(prob1) runs the program

triangular(prob1).cpp -Triangular warping 
Input image name is an input inside (coded)the program(cup1.raw is current input)
output image is set in the program (current output is cup_1_output.raw)
make triangular(prob1) runs the program

Hole filling algorithm-Puzzle matching
hillary_trump.cpp -linear warping 
Input image name is an input(coded) inside the program
(piece.raw,Hillary.raw and Trump.raw)
output image is set in the program 
( output is filled_hillary.raw and filled_trump.raw)
output image(after processing the output image by median filter)
(median_hillary.raw and median_trump.raw)

make hillary_trump runs the program

Homographic transformation and overlay
homographic.cpp-Homographic transformation 
Input image name is an input(coded) inside the program
(field.raw,trojans.raw and tartans.raw)
output image is set in the program 
( output is filled_hillary.raw and filled_trump.raw)
output image(after processing the output image by median filter)
(trojans_output.raw and tartans_output.raw)

make homographic.cpp runs the program
-----------------------------------------------------------------------------------------
Homework 2:
Digital Halftoning 
Ordered_Dithering.cpp-Dithering matrices
Input image name is an input(coded) inside the program
(man.raw)
output image :
"outputman_fourlevels.raw-Fourlevels threshold output
outputman_A_4_Matrix.raw-Dithering by A_4 matrix -output
outputman_bayer_4.raw--Dithering by I_4 matrix -output
outputman_bayer_8.raw--Dithering by I_8 matrix -output
outputman_bayer_2.raw--Dithering by I_2 matrix -output

error_diffusion.cpp-Dithering by Error_Diffusion 
Input image name is an input(coded) inside the program
(man.raw)
output image :
"outputman_floyd.raw"-Output of Floyd's Algorithm
outputman_stucki.raw-Output of Stucki's Algorithm
outputman_jarvis.raw"-Output of the jarvis's Algorithm

Homework 3:
Morphological Image processing

shrink.cpp:Shrinking 
Input image name is an input(coded) inside the program
(squares.raw)
output image is set in the program 
(shrink_output.raw)

make shrink.cpp runs the program

Thin.cpp:Thinning 
Input image name is an input(coded) inside the program
(letterE.raw)
output image is set in the program 
(Thinning_output.raw)

make thin.cpp runs the program

ske.cpp:Skeletionizing 
Input image name is an input(coded) inside the program
(letterE.raw)
output image is set in the program 
(Skeleton.raw)

make ske.cpp runs the program

