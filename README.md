# CNN Sign Language
**Asignatura:** TLY1102

**Evaluación:** Evaluación parcial 2

**Integrantes:** Rodrigo Aedo, Benjamin Figueroa, Martina López.

## Descripción y objetivo del proyecto
Desarrollo de una Red Neuronal Convolucional para la clasificación de imágenes del alfabeto de lengua de señas americana.

El objetivo es implementar y evaluar una CNN mediante TensorFlow/Keras para el reconocimiento de letras de lengua de señas a partir de imágenes para luego comparar su rendimiento con el modelo MLP desarrollado anteriormente.

## Conjunto de datos
Se utilizo el dataset de Sign Language MNIST, que contiene imágenes de manos representando letras del $ASL$ (lengua de señas americana).

Sus características principales son:
*   Imágenes de $28x28$ píxeles.
*   Escala de grises.
*   24 clases correspondientes al abecedario.
*   No se incluyen las letras $J$ y $Z$ ya que requieren movimiento.
*   Los datos estan almacenados en archivos $CSV$ de entrenamiento y prueba.

## Tecnologías utilizadas
*   **Python**
*   **TensorFlow/Keras**
*   **NumPy**
*   **Pandas**
*   **Matplotlib**
*   **Scikit-learn**
*   **Jupyter Notebook**

## Estructura del repositorio
```
Cnn_Sign-Language/
|
├── img/
|   ├── amer_sign2.png
|   ├── amer_sign3.png
|   └── american_sign_language.png
|
├── notebooks/
|   └── CNN_sign.ipynb
|
├──README.MD
└──informe_tecnico.md
```
## Ejecución del proyecto
Para ejecutar este proyecto se necesita Python y un entorno compatible con Jupyter Notebook

1. Descargar o clonar el repositorio.
2. Crear un carpeta data/ para almacenar los archivos "sign_mnist_train.csv" y "sign_mnist_test.csv" previamente descargados.
3. Abrir archivo CNN_sign.ipynb que esta en la carpeta notebooks/.
4. Comprobar que las librerias esten instaladas.
5. Ejecutar las celdas en orden para realizar la preparación, entrenamiento y evaluación de la CNN.
