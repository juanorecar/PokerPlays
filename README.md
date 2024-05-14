# PokerPlays
Trabajo para la asignatura de Procesamiento de Imágenes Digitales

Este proyecto tiene como objetivo desarrollar un sistema automatizado para detectar cartas de póker en imágenes utilizando técnicas de procesamiento de imágenes y visión por computadora. Se emplean herramientas como Python, OpenCV y diversas bibliotecas complementarias para lograr una detección precisa y eficiente.

## Requisitos

- Python 3.x
- OpenCV
- Numpy

1. **Clonar el repositorio:**

    ```bash
    git clone https://github.com/juanorecar/PokerPlays
    ```

2. **Instala las dependencias:**

```
pip install opencv-python numpy
```

## Uso

1. Coloca las imágenes de las cartas en la carpeta `images`.

2. Ejecuta el script `main.py`:

```
python main.py
```

3. **Observa las cartas detectadas en la imagen de prueba `images_test/cartas.jpg`.**

## Detalles Técnicos

El proceso de detección de cartas se realiza en varios pasos:

1. **Extracción de características**: Se utiliza el algoritmo ORB para detectar y describir características en las imágenes de las cartas.

2. **Comparación de características**: Se compara las características de las cartas en la imagen de prueba con las características extraídas de las imágenes de referencia.

3. **Detección de contornos**: Se utilizan técnicas de procesamiento de imágenes para detectar los contornos de las cartas en la imagen de prueba.

4. **Identificación de cartas:** Se identifican las cartas mediante el reconocimiento de contornos y la comparación de características.

## Contribución

¡Las contribuciones son bienvenidas! Si deseas contribuir a este proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (git checkout -b feature/mejora).
3. Realiza tus cambios y haz commit (git commit -am 'Añade nueva característica').
4. Haz push a la rama (git push origin feature/mejora).
5. Crea un nuevo Pull Request.

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

---
