# LogisticRegressionApp

La aplicación se encuentra en el siguiente enlace: https://albertoalmuinha.shinyapps.io/logisticregresion/

El dashboard consta de tres partes:

- Dataset & Parameters:

  1. El primer paso será cargar el fichero .csv con los datos sobre los que queramos aplicar una regresión logística. El fichero debe tener una cabecera y venir separado por comas. Además, los datos deben estar ya preparados para la aplicación del algoritmo. Esto significa que todas las columnas cargadas deben ser numéricas y todos los pasos de preprocesamiento deben estar realizados.
  
  2. Una vez cargado el fichero, modificamos los parámetros que se le pasarán a la función logistic_regression de mi librería LogisticRegression: https://github.com/AlbertoAlmuinha/LogisticRegression
  
  3. Finalmente le damos al botón 'Update' para cargar los resultados. Estos pueden verse en la ventana 'LogisticRegression', donde se muestra la matriz de confusión con diversas métricas así como un plot de la matriz.
  
  4. Cada vez que modifiquemos un parámetro en la ventana 'Data & Parameters' y pulsemos el botón 'Update', se actualizará la información.
  
- Raw Data:

  1. En esta ventana podemos ver los datos cargados. Para ello, introducimos el número de filas que deseamos ver y pulsamos el botón 'Update' de la ventana. También aparecen unos datos en cajas como son el número total de filas del dataset, el número total de columnas y el número de missing values.

- LogisticRegression:

  1. En esta ventana se muestran los resultados de la regresión logística en base a los parámetros de la ventana 'Dataset & Parameters'. Dichos resultados se actualizarán cada vez que se modifica el dataset o algún parametro en la primera ventana y se pulsa el botón 'Update'.
  
  
- Dataset de prueba:

Se puede utilizar el dataset de prueba 'juice.csv' publicado en este repositorio para probar el dashboard.
