# Symmetric-Encryption-Algorithms
Evaluating performance of well known symmetric encryption algorithm

## Environment setup:

**Install PIP in Ubuntu**
```sh
$ sudo apt-get install python-pip
```

**Install Pycrypto and Progress-bar packages from Python PIP**
```sh
$ sudo pip install pycrypto progressbar
```

## Usage
> Format: $ python aes.py mode=file/mem wordlist1 wordlist2 ... wordlistN

```sh
$ python AES/aes.py file res/milNum.txt
```

For multiple source files
```sh
$ python AES/aes.py file res/millionNum.txt res/thousandNum.txt
```
