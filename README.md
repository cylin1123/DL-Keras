# DL-Keras

### Documention

https://keras.io/

### Install Keras
~~~
pip install keras
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




