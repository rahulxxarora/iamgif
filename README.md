
Iamgif
======

![alt tage](https://github.com/rahulxxarora/iamgif/blob/master/animation.gif)

A Python library to convert text to a GIF.


Installation
============

```
pip install iamgif
```


Example
=======

Things to be taken care of:

## Function Arguments

1. Text to be converted to GIF
2. Absolute Path of the detination. Where the file will be created

## General 

1. Use Sudo while running your script, otherwise it won't be able to create the GIF file


### Code

```python

from iamgif import iamgif

iamgif.create("Hello World", '/Users/coderahul/Desktop')
```    
   
### Output

```
Creates a GIF by the name animation.gif in the same directory where the script is executed.
```
