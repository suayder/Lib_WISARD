# Lib_WISARD

This is a simple WISARD (Wilkie, Stonham and Aleksander’s Recognition Device)) neural network library

I have made it only to do some test and get results returned by WISARD, therefore is very a simple implementation but functional.

### What i need

```
Python version 3.5 or higher
numpy 1.14.5
```

When i say these versions is because i have tested in it

### How to use

> All you need is to instanciate the class Wisard putting respectively as parameter *number of rams*, *number of input in each ram* and optionaly the retine sequence to consist in a interable data structure, usually a numpy array.

```
Wisard (n_rams, n_inputs_ram, retine = 0)
```

> At this class we have the following operatins

```
train(array) -> this paramether is a numpy array to be trained

classify(array) -> parameter is also a numpy array to be tested and return the number of RAMs triggered

print_discriminator() -> Does not need to passa parameter, is used usualy to debug code, will print all patterns saved in current discriminator

getN_Rams() -> Return number of RAMs in that discriminator
```

> An example of an application using this lib is showed [here](https://github.com/suayder/Mnist-Wisard)
