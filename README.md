# Edge-detection  edge detection:
Sobiel edge detection: <br/>  The input image is clown.tif <br/> image  -> input images converting to the grays scale and taken height and width of input image<br/>
->vertical edge detection :<br/>
                  [1,0,-1]<br/>
       ->kernel = [2,0,-2]<br/>
                  [1,0,-1]<br/>
-> taken height and width of kernel<br/>
->image_conv create a zero size empty matrix<br/>
->image and kernel multiplying and adding to the ‘s’ variable<br/>
-> ‘s’ stores to the image_conv<br/>
->using cv2_imshow(image_conv) comes to the output image<br/>
->horizonatal edge detection:<br/>
           [1,2,1]<br/>
  ->kernel=[0,0,0]<br/>
           [-1,-2,-1]<br/>
         
  ->taking to the height and width of kernel<br/>
  ->image_conv create a zero size empty matrix<br/>
  ->image and kernel multiplying and adding to the ‘s’ variable<br/>
  -> ‘s’ stores to the image_conv<br/>
  ->using cv2_imshow(image_conv) comes to the output image<br/>
