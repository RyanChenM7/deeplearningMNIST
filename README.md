# deeplearningMNIST
Standard practice in creating a Neural Network, following multiple online guides on how to implement the classic ANN for beginners in Python.
Includes a visualization which shows the neural network in action, by showing what digit it believes the image to be through graphing the output layer.

The file `neural_network.py` is used to train the neural network using the MNIST database based on a couple of variables.
For instance the number of layers, size of layers, # of epochs, learning rate, and mini batch size.

The file 'network_demo' will load up a previously trained (or possibly untrained) neural network, and it will run the AI on samples that are randomly pulled from the database.

</br>

Here are some demo examples, loaded from a network trained for 30 minutes on my laptop (about 96% accuracy).

Very confident in 4.
<img src="https://media.discordapp.net/attachments/795803904075366400/797626663180566618/unknown.png?width=1239&height=677"
     alt=""
     style="float: left; margin-right: 10px;" />
     
Confident in 2.
<img src="https://media.discordapp.net/attachments/795803904075366400/797626747281473566/unknown.png?width=1239&height=677"
     alt=""
     style="float: left; margin-right: 10px;" />

Incorrectly identified the number as 8.
<img src="https://media.discordapp.net/attachments/795803904075366400/797626825156198410/unknown.png?width=1239&height=677"
     alt=""
     style="float: left; margin-right: 10px;" />
