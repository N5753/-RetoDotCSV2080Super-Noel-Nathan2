# -RetoDotCSV2080Super-Noel-Nathan2
Este es el segundo readme y el que contien las actualizaciones más recientes,  quiero comentar que el dataset fue entrenado solo con imagenes de hombres por falta de tiempo
Para ver las imagenes de Output enlace:https://drive.google.com/drive/folders/1TwSiecg_7vwBp529aLmyRMB3Q5t_6DX7?usp=sharing


/// Actualización: 15/09/2019 con un entrenamiento con más exito: 

Epocas del entrenamieto 250
Sigue sin ser entrenado con fotos de mujeres
Se ha introducido estas imagenes en el entrenamiento(los cuatro colores green, blue orange, yellow:
Input(no se llegarón ha usar todas las imagenes porque google colab no lo soportaba):https://drive.google.com/open?id=1iL-fG7MGgAIm4Ad32KOTsDSlEV_vPQ0W  
Target:https://drive.google.com/open?id=1MPPyDrkKX4SWJHLiIR90Ao9eMcZZI4vW

22 imagenes de test:
10 de las cuales han sido usadas en el entrenamiento pero con otros colores en el input(de HF_1 a HF_10)
Imagenes de input en el test:https://drive.google.com/open?id=1VaZrdv-hUSIyMpgOFvaqaVcB0qRfQQyR
Imagenes de output en el test:https://drive.google.com/open?id=1RWSuDg7tkkpG-FcmBTXD0jItaL7FSpxK

Checkpoint: https://drive.google.com/open?id=14An9bc7EcDaGSmaI_xkE3RMxONNBzbhN
Conclusiones: Esta vez el resultado han sido  mejor, se ha visto como sin ser entranado con mujeres  ha detectado el pelo medianamente bien, también se ha visto como a la hora de trabajar con degradados de colores utiliza el color que se a usado en el entramiento, otro punto a recalcar es que como se puede ver en el output, al estar limitados a numero de imágenes para cargar y también no tener un dataset muy diverso de fondos, cuando se introduce una imagen en el input con un fondo que no es demasido parecido a los fondos de las imágenes de input de entrenamiento el programa no sabe pintar muy bien, todavia el programa no ha pintado correctamente las imágenes por su input, lo que hace es mirar el color que contiene el cuadrado de la imagen de input y pinta la imagen con el color que ha sido entrenado que más se le parece. No es perfecto pero va mejorando.
Ahora lo que habria que hacer es añadir más colores para ver si mejorá pero igualmente con los resultados optenidos se puede aprender como reacciona pix2pix ante este tipo de datos.

