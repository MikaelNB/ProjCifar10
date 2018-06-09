# ProjCifar10

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
