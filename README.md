# Logistic-Regression-Gradient-Descent

The file LRTrain.csv contains information from 300 images of malignant (i.e. cancerous) and
benign (i.e., non-cancerous) breast tissue. The data set describes attributes of the cell nuclei in
each image. Each row of the dataset corresponds to one image. For each image, ten different
attributes related to the cell nuclei are recorded:

- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter2/ area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension (a measure of how “complex” the perimeter is)

Because each image contains multiple cell nuclei, three quantities are measured for each of the 10
attributes above: the mean, standard error, and worst case value. This results in a total of 30
features for each image. The goal of this assignment is to train a logistic regression classifier using
gradient descent, which will then be used to predict whether or not each image was taken from
cancerous tissue.

