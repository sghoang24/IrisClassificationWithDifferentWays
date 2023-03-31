# IrisClassificationWithDifferentWays

## Description:
In this repository, I did classfication of Iris Flowers with 4 different ways.
Description about data: iris.csv
- 4 features: "sepal.length", "sepal.width", "petal.length", "petal.width"
- 3 classes: "Setosa", "Versicolor", "Virginica"
- 150 samples

I used Softmax Regression to classify 3 classes of Iris Flower and I experimented with 4 differents ways: Python, Numpy, Tensorflow, Keras
Comparison table of training speed, testing speed, model accuracy for training and test sets:
| Criteria | Python | Numpy | Tensorflow | Keras |
| --- | --- | --- | --- | --- |
| Training time (s) | 4.319 |	0.318 |	10.871 | 15.210 |
| Testing time (s) | 0.000 | 0.000 |	0.003 |	0.215 |
| Training accuracy (%) | 98.33 |	96.67 |	99.17 |	96.67 |
| Testing accuracy (%) | 100 |	100 |	100 |	100 |

## Comment:
- Tensorflow or Keras model had longer training time than model that using Python and Numpy because they applied complicated optimizers algorithm (likes Adam...)
- Loss of 4 models seem to be quite similar with same 1000 epochs. However, loss of Keras Model decrease quite slowly at the beginning compare to other 3 models.
