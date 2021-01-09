# TukeyBox-Method

Pseudocode

----------

fit line using linear regression on all input data

find squared residual distances (from points to line, see linear regression definition)

use Tukey method to find outliers on 'squared residual distances

remove outliers from input data (it is now new input data)

show plots (blue fitted line + green inliers + red outliers)

fit line using linear regression on inlier data

show plots (blue fitted line + green inliers + red outliers)
