# LSBM-Image-Steganography
Simple implementation of Least Significant Bit Matching Image Steganography

### Requirements
- Windows(tested on Windows10 x64)
- Python 3
- Pillow
- Numpy
> ***Set up anaconda environment with the provided `environment.yml`**

### Code execution
The following will run through the code execution in steps of inputs to enter and expected output

1) Execute `python lsbm_img.py` in command prompt
2) A prompt will ask user to enter:
> - **1** for image encoding
> - **2** for image decoding
3) For image encoding(1), user will be prompted to enter the following in order*:
> *After entering each prompt, press enter to submit
> - Full path to image to be encoded(with extension)
> - Image to be encoded
> - Encoded image filename to be saved(without extension)
4) Embedded/stego image will be saved as an image of the original extension/type with the indicated filename 
5) For image decoding(2), user will be prompted to enter:
> - Full path to image to be decoded(with extension)
6) The embedded image(if any) will be shown as output

### Sample images
> - BOSS dataset: http://dde.binghamton.edu/download/ImageDB/BOSSbase_1.01.zip
> - BOWS-2 dataset: http://bows2.ec-lille.fr/BOWS2OrigEp3.tgz
