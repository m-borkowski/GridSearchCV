## GridSearchCV

Grid-searching can be applied across machine learning to calculate the best parameters to use for any given model.
Grid search is the process of performing hyper parameter tuning in order to determine the optimal values for a given model. This is significant as the performance of the entire model is based on the hyper parameter values specified.
The parameters of the estimator used to apply these methods are optimized by cross-validated grid-search over a parameter grid.

## Software and Libraries

Template code is provided in the notebook gridsearchcv-in-biomechanical-features.ipynb

Libraries used in this project:
  * Numpy
  * Pandas
  * Matplotlib
  * Seaborn
  * Sklearn
  
## Data descriptiom

The task consists in classifying patients as belonging to one out of two categories: Normal (100 patients) or Abnormal (210 patients).
Each patient is represented in the data set by six biomechanical attributes derived from the shape and orientation of the pelvis and lumbar spine (each one is a column):

  * pelvic incidence
  * pelvic tilt
  * lumbar lordosis angle
  * sacral slope
  * pelvic radius
  * grade of spondylolisthesis
