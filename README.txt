# Universidad de los Andes

Autores: 
Jorge Sebastian Mora 
Abel Felipe Zambrano
Danny Aldemar Jimenez

## Instalación 

Para ejecutar los diferentes scripts que contiene este proyecto se necesita anaconda python >= 3.0, 
ademas son necesarias las siguiente librerias: 

```bash
conda install tensorflow-gpu
conda install tqdm
conda install numpy
conda install opencv-contrib-python
conda install dlib
conda install PIL
conda install scikit-learn
```

## Para ejecutar main.ipynb se deben seguir los siguientes pasos: 
1. Se debe descargar los dataset del siguiente link:
https://uniandes-my.sharepoint.com/:u:/g/personal/js_moral_uniandes_edu_co/EfNqRxT_2CRHpuBlIuF_fH4BoImihPmgPY3WOuULhLSzRA?e=mEdx6K
2. Se deben descomprimir en la carpeta del proyecto (dentro de la carpeta "Entrega Final").
3. Abrir jupyter notebook y abrir el archivo main.ipynb (El cual se encuentra en la carpeta de este proyecto) 
4. Ejecutar main.ipynb 

Al principio se demorara en moestrar resultados debido a que debe entrenar el PCA con los datos de entrenamiento (esto puede demorar
de 10 a 15 minutos dependiendo del PC) y el tiempo de ejecucion para cada epoca depende de las caracteristicas del pc, si este tiene
una buena tarjeta grafica se puede demorar aprox. 20 minutos, con una tarjeta grafica de gama media se demora aprox 1 hora y sin 
tarjeta grafica se puede demorar hasta 8 horas

## Modelo entrenado 

Si se quiere solo correr el modelo de tensor flow entrenado se de ejecutar el script Trained model run.ipynb, solo se necesitan las 
librerias previamente mencionadas, (No se requiere dataset para este script) y al ejecutarlo se generara una grilla de imagenes. 

## License
