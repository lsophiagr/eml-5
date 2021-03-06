# Laboratorio 5 馃馃馃

## Regresi贸n Lineal Regularizada

El juego de datos proporcionado es parte de la plataforma Kaggle, dentro del cual se muestran diferentes par谩metros que suelen ser considerados por las universidades para admitir a los postulantes en los programas de postgrado (maestr铆as), adem谩s se muestra la probabilidad de admisi贸n de estas personas.

1. GRE Scores ( out of 340 )
2. TOEFL Scores ( out of 120 )
3. University Rating ( out of 5 )
4. Statement of Purpose and Letter of Recommendation Strength ( out of 5 )
5. Undergraduate GPA ( out of 10 )
6. Research Experience ( either 0 or 1 )
7. Chance of Admit ( ranging from 0 to 1 )

Para este ejercicio se le pide que proporcione un modelo de regresi贸n lineal multidimensional regularizada que prediga la admisi贸n del alumno usando todas las caracter铆sticas que considere necesarias. A continuaci贸n se mencionan las generalidades de los pasos sugeridos a realizar.

1. Leer el archivo CSV proporcionado (Admission_Predict.csv, https://www.kaggle.com/mohansacharya/graduate-admissions) y almacenarlo en un np.array para ser trabajado en el notebook.
2. Ajustar un modelo lineal (polin贸mico) en base al juego de datos cargado que relacione cualquier subconjunto propio de las variables de los indicadores seleccionados con la probabilidad de admisi贸n.
3. Utilice la implementaci贸n regularizada de la regresi贸n lineal que mejor se ajuste a los datos.
4. Aseg煤rese de usar el lambda que mejor apoye al modelo que ha implementado para describir y
predecir la informaci贸n sobre la nube de datos.
5. Haga un an谩lisis sobre sus hallazgos, donde mencione claramente las razones por las que considera
que su modelo es bueno justificando adecuadamente as铆 como el lambda usado y las evidencias correspondientes.
