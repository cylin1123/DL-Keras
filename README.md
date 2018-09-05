# DL-Keras

### Python version
* Version :  3.5.2
### Documention

https://keras.io/

### Install Keras
~~~
pip3 install keras
pip3 install h5py
~~~

### Initial model
~~~
from keras.models import Sequential
model = Sequential()
~~~
### Stacking layers
~~~
from keras.layers import Dense
model.add(Dense(units=64, activation='relu', input_dim=100))
model.add(Dense(units=10, activation='softmax'))
~~~




