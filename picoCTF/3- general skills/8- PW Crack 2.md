# Reto
# Descripcion
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/14/level2.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/14/level2.flag.txt.enc) in the same directory too.
# Solucion

```
affogato1-picoctf@webshell:~$ nano level2.py         

affogato1-picoctf@webshell:~$ python
Python 3.10.12 (main, Feb  4 2025, 14:57:36) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print(chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39))
4ec9

affogato1-picoctf@webshell:~$ python level2.py 
Please enter correct password for flag: 4ec9
Welcome back... your flag, user:
picoCTF{tr45h_51ng1ng_9701e681}
```
### Flag: picoCTF{tr45h_51ng1ng_9701e681}
# Notas
Es lo mismo que el anterior, ahora la contraseña estaba encriptada en hexadecimal, asi que use python para desencriptarla
# Referencias
