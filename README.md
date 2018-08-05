# PCA-and-OVILETTI

## Principal Component Analysis(PCA)
In machine learning problems there often involves tens of thousands of features for each training instance. This can be a problem as it makes our training extremely slow and prone to overfitting (refer to overfitting section). This problem is commonly referred to as the curse of dimensionality.
Because of the issues associated with the curse of dimensionality, it is necessary to reduce the number of features/dimensions considerably to help increase our model’s performance and enables us to arrive at an optimal solution for our machine learning model. Fortunately, in most real life problems, it is often possible to reduce the dimensions of our training set, without losing too much of the variance within our data.

By reducing the dimensions of our training set, we can increase the speed of our training, and reduce our dataset down to two or three dimensions, making it easier to perform data visualisations (clustering, patterns).

## Olivetti faces dataset
This dataset contains a set of face images taken between April 1992 and April 1994 at AT&T Laboratories Cambridge. The sklearn.datasets.fetch_olivetti_faces function is the data fetching / caching function that downloads the data archive from AT&T.

As described on the original website:

There are ten different images of each of 40 distinct subjects. For some subjects, the images were taken at different times, varying the lighting, facial expressions (open / closed eyes, smiling / not smiling) and facial details (glasses / no glasses). All the images were taken against a dark homogeneous background with the subjects in an upright, frontal position (with tolerance for some side movement).

The eigenfaces is one of the most popular approaches to represent an image, with the basic idea that the top k component eigenvectors (eigenfaces) represent as much variance as possible. This criterion need not to be meaningful. It is also susceptible to illumination and background around the face.
