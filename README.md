# action_recognition using OpenCV and Python

Libraries needed

cv2

imutils

numpy

sklearn

# concepts used in this module:

# Contours

The outline or the boundary of the object of interest. This contour could easily be found using OpenCV’s cv2.findContours() function. Be careful while unpacking the return value of this function, as we need three variables to unpack this tuple in OpenCV 3.1.0 - Contours.

# Bitwise-AND

Performs bit-wise logical AND between two objects. You could visually think of this as using a mask and extracting the regions in an image that lie under this mask alone. OpenCV provides cv2.bitwise_and() function to perform this operation - Bitwise AND.

# Euclidean Distance

This is the distance between two points given by the equation shown here. Scikit-learn provides a function called pairwise.euclidean_distances() to calculate the Euclidean distance from one point to multiple points in a single line of code - Pairwise Euclidean Distance. After that, we take the maximum of all these distances using NumPy’s argmax() function.

# Convex Hull

You can think of convex hull as a dynamic, stretchable envelope that wraps around the object of interest.

