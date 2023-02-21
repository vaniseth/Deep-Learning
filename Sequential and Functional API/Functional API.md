# FUNCTIONAL API KERAS

* In Functional API, we work with connecting the layers in parallel.
* The input is copied to say two different layers and the out of them is added to the output layer.
* There can be as many parallel layers a we want.
* Each layer is passed as a function.

### ADVANTAGES OF FUNCTIONAL API

* It provides more flexibility to define the models.
* Can define multiple inputs, output models
* Have the flexibility to split and share the intermediate layers.
* Build start of the art model architecture of any custom architecture.

### LAYERS

**LOWER LAYER:** The input is the lower layer thus **lower layers** are those which are close to the input layer.

**UPPER LAYER:** Output layer is the upper layer this **upper layers** are those which are close to the output layer.
