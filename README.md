# OpenCV
OpenCV-Python is a library of Python bindings designed to solve computer vision problems. cv2.copyMakeBorder() method is used to create a border around the image like a photo frame. 

# The borderType flags are described below: 
 

cv2.BORDER_CONSTANT: It adds a constant colored border. The value should be given as a keyword argument
cv2.BORDER_REFLECT: The border will be mirror reflection of the border elements. Suppose, if image contains letters “abcdefg” then output will be “gfedcba|abcdefg|gfedcba“. 
cv2.BORDER_REFLECT_101 or cv2.BORDER_DEFAULT: It does the same works as cv2.BORDER_REFLECT but with slight change. Suppose, if image contains letters “abcdefgh” then output will be “gfedcb|abcdefgh|gfedcba“. 
cv2.BORDER_REPLICATE: It replicates the last element. Suppose, if image contains letters “abcdefgh” then output will be “aaaaa|abcdefgh|hhhhh“. 

# Sample Image
![download](https://github.com/RidhiSood22/Image-processing---Image-Border/assets/142926361/058815aa-0ae3-4039-ac7c-a1314e2b1329)

 
 
