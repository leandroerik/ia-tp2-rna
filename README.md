# Generales
* Para instalar librerias necesarias:
<br> `python.exe -m pip install tensorflow scikit-learn matplotlib pandas numpy opencv-python pillow ipywidgets`

* Al ejecutar desde VSCode, poner en la terminal:
<br>  `pip install tensorflow scikit-learn matplotlib pandas numpy opencv-python pillow ipywidgets`


# Nuestro Trabajo
* Ubicación: `/TP2`.

* Se consideran imágenes de 6 personajes de Disney:
   * Mickey.
   * Minnie.
   * Donald.
   * Daisy.
   * Goofy.
   * Pluto.

* Técnicas de _data augmentation_ usadas para aumentar la cantidad de imánges:
   * Flip horizontal y flip vertical.
   * Rotación a favor de las agujas del reloj, rotación en contra de las agujas del reloj.
   * Rotación de 180º.
   * Aumento y diminución de brillo.
   * Aumento y diminución de contraste.
   
* Se decide usar imágenes en color con un tamaño de 40x40 píxeles.

* Respetando tanto el "70-30" de [EV-P] como el "80-20" de [E-V], los datos se reparten de esta manera:
    * [E] Entrenamiento:  56%
    * [V] Validación:     14%
    * [P] Prueba:         30%

# RNA-MLP-procesar-imagenes.ipynb
* Lo compartido por el profesor desde Google Colab pero levantado localmente.
* Ubicación: `/backup`.

