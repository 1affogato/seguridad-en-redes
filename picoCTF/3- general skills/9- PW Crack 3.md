# Reto
# Descripcion
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/17/level3.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/17/level3.flag.txt.enc) and the [hash](https://artifacts.picoctf.net/c/17/level3.hash.bin) in the same directory too.There are 7 potential passwords with 1 being correct. You can find these by examining the password checker script.
# Solucion

```
affogato1-picoctf@webshell:~$ nano level3.py 

affogato1-picoctf@webshell:~$ python level3.py 
Please enter correct password for flag: 87ab
Welcome back... your flag, user:
picoCTF{m45h_fl1ng1ng_cd6ed2eb}
```
### Flag: picoCTF{m45h_fl1ng1ng_cd6ed2eb}
# Notas
Dentro del script viene una lista con todas las contraseñas, sorpendentemente le atine a la primera
# Referencias
