# Kaggle Project for Applied Machine Learning

This is the repository for the 1<sup>st</sup> National Data Science Bowl Kaggle Challenge: Plankton Image Classification ([here](https://www.kaggle.com/c/1stdsbowl-in-class) or [here](https://www.kaggle.com/c/datasciencebowl)). This project was part of the Applied Machine Learning course for the MSc Information Studies at the University of Amsterdam ('18-'19).

## Goal

The goal of this project was to maximize test accuracy for the unknown labels of the `test_images`. In the original challenge the goal was to minimize Log Loss, but this was not the case for this project.


## Notebooks

There are multiple Jupyter Notebooks in the repo. Multiple techniques have been applied in order to solve this problem. Each notebook corresponds to a different approach.

## Evaluation

Submissions were evaluated using the Category Accuracy. Each image had been labeled with one true class. For each image, we submitted our predicted class. The formula is then:

### Submission Format

We submitted csv files with the image name and the predicted class label. The order of the rows did not matter. The file needed to have a header and looked like the following:

```
image,class
1.jpg,0
10.jpg,99
...
etc
```
