# Edge-detection  edge detection:
Sobiel edge detection:  The input image is clown.tif image  -> input images converting to the grays scale and taken height and width of input image
  ->vertical edge detection :
            [1,0,-1]
  ->kernel = [2,0,-2]
            [1,0,-1]
  -> taken height and width of kernel
  ->image_conv create a zero size empty matrix
  ->image and kernel multiplying and adding to the ‘s’ variable
  -> ‘s’ stores to the image_conv
  ->using cv2_imshow(image_conv) comes to the output image
  ->horizonatal edge detection:
         [1,2,1]
  ->kernel=[0,0,0]
         [-1,-2,-1]
         
  ->taking to the height and width of kernel
  ->image_conv create a zero size empty matrix
  ->image and kernel multiplying and adding to the ‘s’ variable
  -> ‘s’ stores to the image_conv
  ->using cv2_imshow(image_conv) comes to the output image
