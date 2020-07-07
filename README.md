# Lateinische-Texte-Klassifizieren
I have tried to train an artificial neural network to decide, if a given text in latin language is written in the classical time of the roman empire or in the middle ages.
I have experimented with different types of networks. I have used Python with Tensorflow.

The main result was:

1.) Trained with a broad mixture of different authors from different centuries the network is not able to detect patterns or rules, it can only guess.

2.) Trained with two selected authors, the network is able to detect the difference, but with clear overfitting. 

The file "Latein.zip" attached is a zipped directory containing the Python code and all files (including the data) and subdirectories needed. 
The path, where it is unzipped, must be specified in the code (in the variable provided for this purpose).
The directory containes also a file "Liesmich" (sorry, it's in german) with further explanations. 
