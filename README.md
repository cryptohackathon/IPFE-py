# IPFE-py

IPFE-py (Inner Product Functional Encryption in python) is intended to provide functional encryption support in python. This project uses the base as the CiFEr library which is originally developed in C by the fentec group. 

As the python is one of the widely used languages, this is my small try to make use of IPFE in python. This function can replace numpy dot function and can securely compute the dot product of x and y (with encrypted x) as per the properties of functional encryption. 

# How to Run the Code?

This code is ready to run as it is without any changes. Just download this code and open CryptoHackathonDemo.ipynb file using anaconda or google colab. Make sure that mission6.so file is in the same folder as of CryptoHackathonDemo.ipynb. 


# Requirements

First build the CiFEr from https://github.com/fentec-project/CiFEr.

After build is successful, you'll get libcifer.so in the '/usr/local/lib'. Paste the same in the python lib directory.
