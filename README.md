# LogisticRegressionApp

[![Lifecycle:
maturing](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)

The app is hosted in the next link: https://albertoalmuinha.shinyapps.io/logisticregresion/

The dashboard has three main panels:

- Dataset & Parameters:
  
  1. The first step will be to load the .csv file with the desired data. This file must have a header and with comma separation. The data must have prepared to apply the algorithm. This means that all loaded columns must be numeric and all preprocess steps well done.
  
  2. Una vez cargado el fichero, modificamos los parámetros que se le pasarán a la función logistic_regression de mi librería LogisticRegression: https://github.com/AlbertoAlmuinha/LogisticRegression
  
  2. Once we have loaded the file, we can modify the parameters of the [logistic_regression function](https://github.com/AlbertoAlmuinha/LogisticRegression) in the corresponding boxs.

  3. Finally, we click the 'Update' botton to load the results. This results can be seen in the panel 'LogisticRegression', where you can find the confusion matrix, different metrics and a confusion matrix plot.
  
  4. Also we can see in this panel graphics like the correlations between variables for train and test datasets. We can also find the number of rows for both datasets and the number of positive and negative values of the target variable.
  
  5. Each time we modify the panel 'Data & Parameters' and click the 'Update' botton, the displayed information will be modified.
  
- Raw Data:
  
  1. In this panel we can see the loaded data. For that, we pick the number of rows we want to see and click the 'Update' botton. We can also see the number of rows, columns and missing values.

- LogisticRegression:

  1. In this panel the results of the logistic regression function are displayed.
    
- Dataset:

You can use the 'juice.csv' dataset published in this repository to try the dashboard.

## Issues

If you find some bug, error or doubt, please tell me [here](https://github.com/AlbertoAlmuinha/LogisticRegressionApp/issues) .

## License

This App is licensed under GNU Lesser General Public License v3.0.

> Permissions of this copyleft license are conditioned on making available complete source code of licensed works and modifications under the same license or the GNU GPLv3. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights. However, a larger work using the licensed work through interfaces provided by the licensed work may be distributed under different terms and without source code for the larger work.
