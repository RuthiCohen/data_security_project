# Introduction - data_security_project
The software implements the algorithm which is proposed in the article "Robust Edge based Image Steganography through Pixel Intensity Adjustment".
This system is a software for encrypting a message(string format) in a colored/grayscale image as well as extracting.

We have suggested 2 improvements to this algo.
1.Adding a layer of protection for the information hidden in the message - we encrypted the information before embedding it in the image
so even if it is possible to retrieve the message it will not be possible to decrypt the cipher.
2.According to the article, the encryption works only on gray images, we added in code support for colorful images too.

The code before the enhancements can be found in the algorithm-lsbm.py file (according to the article)
● In the improvements-after-algorithm-lsbm.py file you can find the code with our implementations of suggestions 1,2. 
● In the finalCode.py file you can find our final product

○ The encode.py file you can find the implementation of the encoded mssg. 
Enter the name of the image in the field "image_input" and an encodedd image is the output with the message embedded in the file named in "image_output" field.
Then run the code contained in the decode.py file.
In the "image_output" field we enter the name of the image encoded in the first step → and we will receive the message encoded.

# 💻 Technologies 

#### Requirements: <br />
  * Windows(tested on Windows10x64)
  * Python 3
  * Numpy
  * Cv2
  
  
#### 🛠️ Launch: <br /> 
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
