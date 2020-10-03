<h2 align="center"> Dog_Breed_Classifier </h2>

![forks](https://img.shields.io/github/forks/ClownMonster/Dog_Breed_Classifier)
![license](https://img.shields.io/github/license/ClownMonster/Dog_Breed_Classifier)
![stars](https://img.shields.io/github/stars/ClownMonster/Dog_Breed_Classifier)

<h3>Abstract: </h3>
<p>The neural network is the most advanced method at the moment to train the system to do a task. Among them CNN (convolution neural network )  and its derivatives are the most used for training the system to identify and classify images and in computer vision.</p>
</br>
<h3>Network Used: </h3>
<p> Convolution Neural Network (CNN)</p>




</br>
<h3>Layers in the network : </h3>

* cnn.add(Conv2D(filters=128,kernel_size=5,activation='relu',input_shape=[64,64,3]))

* cnn.add(MaxPool2D(pool_size=3,strides=1))

* cnn.add(Dropout(0.2))

* cnn.add(BatchNormalization())

* cnn.add(Conv2D(filters=64,kernel_size=3,activation='relu'))

* cnn.add(MaxPool2D(pool_size=3,strides=1))

* cnn.add(Dropout(0.2))

* cnn.add(BatchNormalization())

* cnn.add(Conv2D(filters=32,kernel_size=3,activation='relu'))

* cnn.add(MaxPool2D(pool_size=3,strides=1))

* cnn.add(Dropout(0.2))

* cnn.add(BatchNormalization())

* cnn.add(Conv2D(filters=32,kernel_size=3,activation='relu'))

* cnn.add(MaxPool2D(pool_size=3,strides=1))

* cnn.add(Dropout(0.2))

* cnn.add(BatchNormalization())

* cnn.add(Conv2D(filters=32,kernel_size=3,activation='relu'))

* cnn.add(MaxPool2D(pool_size=3,strides=1))

* cnn.add(Dropout(0.2))

* cnn.add(BatchNormalization())


* cnn.add(GlobalAveragePooling2D(data_format='channels_last'))

* cnn.add(Dense(units=10,activation='softmax'))</p>


</br>
<h3>Accurracy Score: </h3>
<p>32%. Due to lack of computation power number of epochs had to be set to less, so the accuracy is low.</p>

</br>


</br>
<h3>Dataset : Data set is taken from kaagle </h3>

</br>
<h3>Contributors : </h3>
  
   <h4>Sanjay urs K P , Jyothi B R, Karthik B S, Nayana , Mohan Kumar K</h4>
 
  
<h3>Licensed To : MIT</h3>

<h3>Images : </h3>


  
