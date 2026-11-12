# Model Fitness: predicción de cancelación de clientes

Proyecto del Sprint 14 del curso de Data Analyst en TripleTen.

## El problema
Model Fitness es un gimnasio que pierde clientes sin saber a quiénes ni por qué. El objetivo fue anticipar qué clientes están en riesgo de cancelar y entender qué distingue a quienes se quedan de quienes se van.

## Los datos
4,000 clientes. Cancelaron 1,061 (26.53 %) y permanecieron 2,939 (73.48 %). Variables: antigüedad, asistencia reciente, duración del contrato, participación en actividades grupales, distancia, empresas asociadas y recomendación de amigos.

## Modelos
Regresión logística vs. bosque aleatorio (Random Forest), validados contra la referencia simple de predecir que nadie cancela. El bosque aleatorio fue el mejor: 92.75 % de exactitud, 88.50 % de precisión y 83.49 % de recall (detectó 177 de 212 cancelaciones en validación).

## Segmentación
5 grupos de clientes. Los de mayor riesgo son el clúster 3 (52.66 % de cancelación) y el clúster 0 (45.04 %); juntos reúnen el 78.04 % de todas las cancelaciones.

## Herramientas
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.

## Cómo ver el análisis
Abre el archivo Proyecto_Sprint_14_Model_Fitness.ipynb en este repositorio.
