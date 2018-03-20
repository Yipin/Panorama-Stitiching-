Panorama-Stitiching
====================
Automated Panorama Stitching

1. anms.m implements adaptive non maximal supression.

2. get_features.m extracts 8*8 feature descriptors of interest points.
   get_features_rotation_invia.m add rotation invariance during the feature extraction.(Extra credit)

3. define_correspondence.m calls the anms.m, get_feature.m and get_feature_rotation_invia.m, you can change the value of  "is_rotation_invariance" to decide whether adding rotation invariance or not. Then, it implements feature matching based on Lowe's "ratio test".

4. calculate_transform.m calculates the homography H by SVD method.

5. ransac.m recovers the homography robustly using RANSAC algorithm.

6. proj6_recognition.m implements Panorama recognition: automatically discover and stitch the images from one panorama together from a set of images.

Project webpage: http://cs.brown.edu/courses/cs129/results/proj6/zyp/
