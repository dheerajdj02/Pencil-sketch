# Pencil-sketch
Pencil sketch made using image or live video

## How to run
   In your IDE run [test.py](https://github.com/dheerajdj02/Pencil-sketch/blob/master/text.py)

## Library Required
  - Opencv2
  - keras
  - numpy
  - matplotlib
  Install above library using pip or conda
  
### Change the value to get more accurate
 
   canny_edges = cv2.Canny(img_gray_blur, **10**, **70**)
   
   ![sektch](https://user-images.githubusercontent.com/61626863/81550568-108ccc00-939e-11ea-8204-6da805d31614.png)

   Changeing the value in canny get more edges
   
   canny_edges = cv2.Canny(img_gray_blur, **5**, **50**)
   
   
   ![Sketch1](https://user-images.githubusercontent.com/61626863/81550633-2b5f4080-939e-11ea-9a8b-e7f20b18abe4.png)
     

