# opencv-image-transform
Opencv image transformation with Python

It is basic image transformation for data augmentation.


### show_cv_image
This function is for showing image at jupyter notebook. 
Opencv uses BGR color scheme, but normal color scheme is RGB. 
So, I convert BGR to RGB and show the image by using pyplot.

### flip_image_vertical
This function is fliping image vertically. The parameter "1" of cv2.flip is meaning vertical change.

### flip_image_horizontal
This function is fliping image horizontally. The parameter "0" of cv2.flip is meaning horizontal change.

### brightness
The value parameter is meaning the degree of lightening. It makes the image brighter.

### darkness
The value parameter is meaning the dergree of darkening. It makes the image darker.

### rotation
The angle parameter is meaning the degree of rotation. When entering a positive value at angle, it rotates counterclockwise.

### zoom_in
The scale parameter is meaning the degree of expansion. This zoom in randomly. 
The smaller the scale parameter value, the larger the magnification ratio.
