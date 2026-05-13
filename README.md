# ARIMA-p-d-q-

1. Considera nuevamente la información histórica de temperaturas promedio por año para la ciudad de Nueva York en el período 1870 -2020.

2. Determina mediante la gráfica de prueba de Dickey-Fuller si los datos son estacionarios considerando una base de entrenamiento del 90% del total. En caso negativo, aplica tantas diferencias como sea necesario para alcanzar la estacionariedad y comenta al respecto.

<img width="480" height="380" alt="image" src="https://github.com/user-attachments/assets/733707e8-c1d8-4adc-8cd4-48df336927f6" />

No hay evidencia estadística para rechazar H0 (y por lo tanto decir que la serie es estacionaria). 

<img width="486" height="381" alt="image" src="https://github.com/user-attachments/assets/05466f31-cf94-4400-8dbd-12cfd1aff304" />

La serie transformada de diferencias si es estacionaria. 

3. Obtén los parámetros óptimos mediante el índice de información de Akaike (a partir del resultado anterior), compara al menos 6 combinaciones diferentes de parámetros p, d y q en el modelo general ARIMA(p, d, q).

<img width="519" height="379" alt="image" src="https://github.com/user-attachments/assets/b5b1f4e4-3e19-49ca-ab28-c0499d33a4f4" />

4. Haz una gráfica (al resultado óptimo obtenido previamente) que incluya los datos de prueba, los de entrenamiento, y las predicciones puntuales y de intervalo para la base de prueba.

<img width="985" height="269" alt="image" src="https://github.com/user-attachments/assets/87276b4f-e6d2-4c62-8e87-42ec2085d6ae" />

5. Responde a la pregunta: ¿Son confiables sus pronósticos? Justifica tu respuesta con los indicadores del error.

De acuerdo con el rmse y el mape, el pronóstico se equivoca aproximadamente en ±1.24 unidades y un 1.87% de las veces por lo que los resultados se pueden considerar bastante confiables.
