# **Explanation**
#### **Image Loading and Grayscale Conversion:** The input image is read and converted to grayscale for easier processing.
#### **Edge Detection:** The Canny edge detector is used to find the edges in the image.
#### **Contour Detection:** The contours are found in the image. Each contour represents a potential shape.
#### **Polygon Approximation:** Each contour is approximated to a simpler polygon using cv2.approxPolyDP.
#### **Shape Classification and Drawing:** The contours are classified into triangles, rectangles, or circles based on the number of vertices in the approximated polygon. The shapes are then drawn on a blank canvas.
#### **Output:** The final image with regularized shapes is saved.
