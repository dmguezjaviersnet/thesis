A modern pothole detection technique using deep learning - kumar2020modern

Este artículo propone un modelo basado en deep learning  
que puede detectar baches de forma temprana usando imágenes y videos.

Este modelo se basa en Transfer Learning, Faster Region-based
Convolutional Neural Network(F-RCNN) y
Inception-V2

 Here,
convolution and pooling have been used for feature
extraction. Adam optimizer is used to reduce the

cost function and sigmoid function for output
predicted values between 0 and 1.

 fine-tuning

 We’ve selected the model named
“F-RCNN inception v2”.

En este trabajo propusimos un sistema para detectar
baches en tiempo real en imágenes/videos capturados por
una cámara montada en el vehículo y para dar una
alertar al conductor sobre el bache en la carretera de enfrente
del vehículo Además, nuestro sistema detectará el
ubicación del bache y subir el mismo en el mapa
(reflejado en la aplicación de Android desarrollada por nosotros) para que
otros usuarios que no tienen una cámara montada en su
El vehículo puede recibir una alerta sobre el bache usando el
solo aplicación (sin embargo, este es nuestro trabajo futuro). En esto
sistema, utilizamos la famosa y compleja CNN
arquitecturas como Inception v1 (GoogLeNet),
inicio v2 y finalmente seleccione inicio v2 en nuestro
sistema.

 CNN typically has three layers: a convolutional layer, a pooling layer, and a fully connected layer.
 
La propuesta moderna basada en para un método de detección de baches
usando la técnica de transfer Learning para detectar baches en videos/
imágenes en tiempo real. Este método usa las técnicas conocidas comúmente  
como F-RCNN y "Inception v2 model" . Con la técnica de Transfer Learning
se hace uso del conocimiento ganado resolviendo un problema y aplicarlo
a un problema diferente pero relacionado con este. En esta técnica 
primero, seleccionan un modelo preentrenado y luego aplicar fine tunning.


