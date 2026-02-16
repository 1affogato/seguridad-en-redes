# Reto
# Descripcion
Fix the syntax error in this Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/26/fixme1.py)
# Solucion

```
affogato1-picoctf@webshell:~$ python fixme1.py 
  File "/home/affogato1-picoctf/fixme1.py", line 20
    print('That is correct! Here\'s your flag: ' + flag)
IndentationError: unexpected indent
affogato1-picoctf@webshell:~$ nano fixme1.py 
affogato1-picoctf@webshell:~$ python fixme1.py 
That is correct! Here's your flag: picoCTF{1nd3nt1ty_cr1515_09ee727a}
```
### Flag: picoCTF{1nd3nt1ty_cr1515_09ee727a}
# Notas
Estaba mal identado el codigo en python, tuve que meterme a editarlo para que me diera la bandera
# Referencias
