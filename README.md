# ProjCifar10 (English)
___
Student:
	Mikael Nycander Barúa

2 CNNs were trained:
	Cifar10-Keras-Tensorflow-Binary_crossentropy-93.5%
	Cifar10-Keras-Tensorflow-Categorical_crossentropy-67.3%
Used versions:

	miniconda(para entorno virtualizado de python=3.5)
	
	jupyter		1.0.0
	tensorflow 	1.2.0
	keras 		2.0.5
	h5py + hdf5 	2.6.0 y 1.8.16 respectivamente
	matplotlib 	2.0.2
	numpy 		1.11.3
The directory "input/" contains 3 images which were used
to test the generated models. (Use Case Example)

The directory "models/" contains models which were obtained 
from the training phase and can be reused without the 
requirement to re-train the network each time.

The convolutional neural network Binary_crossentropy has 
93,5% accuracy in comparison to 67% obtained from Categorical_crossentropy.
Data obtained from Cifar10-Keras-Tensorflow-Binary_crossentropy-93.5%
shows a better result; however, overfitting can't be discarded due to the
fact that when new images are fed, error increases.

___
# ProjCifar10 (Español)

Alumno: 
	Mikael Nycander Barúa

Se entrenaron 2 CNNs:
	Cifar10-Keras-Tensorflow-Binary_crossentropy-93.5%
	Cifar10-Keras-Tensorflow-Categorical_crossentropy-67.3%

Se utilizó:

	miniconda(para entorno virtualizado de python=3.5)
	
	jupyter		1.0.0
	tensorflow 	1.2.0
	keras 		2.0.5
	h5py + hdf5 	2.6.0 y 1.8.16 respectivamente
	matplotlib 	2.0.2
	numpy 		1.11.3

La carpeta "input/" contiene 3 imágenes que fueron usadas
para probar la clasificación en base a los modelos
generados. (Ej. de caso de uso)

La carpeta "models/" contiene los modelos que se generaron
de los entrenamientos para poder ser reutilizados sin
necesidad de re-entrenar la red cada vez.

La red neuronal convolucional con Binary_crossentropy
tiene precisión de 93.5% en comparación con Categorical_crossentropy
con 67.3%. Según los datos Cifar10-Keras-Tensorflow-Binary_crossentropy-93.5%
es mejor, sin embargo no puede descartarse el overfitting debido a que al aplicarse
a imagenes nuevas existe mayor error.
