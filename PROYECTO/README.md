# Análisis de Sentimientos en Español

Este proyecto implementa un modelo de análisis de sentimientos para frases en español, clasificando los textos en tres categorías: **Alegre**, **Neutral** y **Triste**. Incluye un notebook de entrenamiento y una aplicación web para probar el modelo.

## Estructura del proyecto

- `sentiment_analysis_training.ipynb`: Notebook para entrenar el modelo y guardar el vectorizador.
- `app.py`: Aplicación web Flask para analizar sentimientos en frases nuevas.
- `modelo_sentimientos.pkl`: Modelo entrenado guardado.
- `vectorizador.pkl`: Vectorizador de texto guardado.

## Requisitos

- Python 3.8+
- Flask
- scikit-learn
- pandas
- numpy

Instala las dependencias con:

```sh
pip install flask scikit-learn pandas numpy
```

## Uso

1. **Entrena el modelo**  
   Ejecuta el notebook `sentiment_analysis_training.ipynb` para generar los archivos `modelo_sentimientos.pkl` y `vectorizador.pkl`.

2. **Ejecuta la aplicación web**  
   En la terminal, ejecuta:

   ```sh
   python app.py
   ```

   Abre tu navegador en [http://127.0.0.1:5000](http://127.0.0.1:5000).

3. **Analiza frases nuevas**  
   Ingresa una frase en español y obtén el sentimiento predicho.

## Autor

Camila Paredes & Herrera Anahy

---
