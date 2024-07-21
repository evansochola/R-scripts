# Boston

This project uses a small example dataset that has the median values of houses for 506 suburbs in Boston, USA. The dataset is all numeric values. There are 12 input columns (fields) in the dataset and 506 rows.

The input fields are:\

| Input Field | Description                                                                                                  |
|-------------|--------------------------------------------------------------------------------------------------------------|
| age         | Proportion of owner-occupied units built prior to 1940                                                       |
| b           | Measure of ethnic diversity by town.                                                                         |
| chas        | Charles River dummy variable (=1 if tract bounds river; 0 otherwise).                                        |
| crim        | Per capita crime rate by town                                                                                |
| dis         | Weighted mean of distances to five Boston employment centres. rad index of accessibility to radial highways. |
| indus       | Proportion of non-retail business acres per town.                                                            |
| lstat       | Lower status of the population (percent).                                                                    |
| nox         | Nitrogen oxides concentration (parts per 10 million).                                                        |
| ptratio     | Pupil-teacher ratio by town.                                                                                 |
| rm          | Average number of rooms per dwelling.                                                                        |
| tax         | Full-value property-tax rate per \\\$10,000                                                                  |
| zn          | Proportion of residential land zones for lots over 25,000 sq. ft.                                            |

| Output field | Description                                            |
|--------------|--------------------------------------------------------|
| mdev         | Median value of the homes in that suburb (in \$1,000s) |

`mdev` is the field that we would like to predict based on the other fields.

## 
