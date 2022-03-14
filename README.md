# Introduction - data_security_project
The software implements the algorithm which is proposed in the article "Robust Edge based Image Steganography through
Pixel Intensity Adjustment".
This system is software for encrypting a message(string format) or image within a grayscale image as well as extracting.
The software has 2 operations: embedding and extraction, in both the cover image is divided into 3x3 blocks as a basis for the work of the algorithm proposed in the article.

In the first block (top left corner) the length of the message or alternatively the dimensions of the image will be embedded. Therefore there are restrictions on the length of the message / image size.
In the other blocks, the message / image is embedded according to the pairs of pixels in each block.
If you choose to embed an message, as part of the upgrades it will undergo a double encryption process.
If you choose to embed an image, it will go through a process of conversion to a string that symbolizes the pixels in binary.
At the extraction stage the message or image respectively will appear Perfectly as embedded.

# 💻 Technologies 

#### Requirements: <br />
  * Windows(tested on Windows10x64)
  * Python 3
  * Numpy
  * Cv2
  
  
#### Code execution: <br /> 
The following will run through the code execution in steps of inputs to enter and expected output

Execute python LSBM-algorithm.py in command prompt<br/>
1.In main function user is required to enter:<br />
    input image to "input_image" field<br />
    output image to "output_image" field<br />
    secret message to "secret_data" field<br />
2.The main function will embeed the secret message using LSBM algorithm and will decode the message<br />
3.During program running "Threshold binary inverse image (in gray)", "Image edges detection using canny algorithm"
will be printed to the screen<br />
4.At the end of the program image in the entered name of "output_image" will be created automatically in the src path<br />

# 📗 Authors
Tair Shriki <br />
Ruth Bracha Cohen <br />
Margalit Lionov <br />
Ravit Clark <br />
