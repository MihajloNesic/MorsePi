# MorsePi
Morse Code translator for Raspberry Pi and PiFace Digital 2

## Clone git
`git init` <br />
`git clone https://github.com/MihajloNesic/MorsePi.git` <br />
`cd MorsePi`

## Run with
`python3 morse.py`

## Personalizing
This part of code:
```
for ch in inp:
	print(CODE[ch.upper()])
```
..prints the translated text input into morse code. You can comment/delete this part if you don't want it.
_________

Change this number `led=0` to set which LED on PiFace will light.

