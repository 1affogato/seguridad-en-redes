# Reto
# Descripcion
Can you find the flag in [file](https://challenge-files.picoctf.net/c_fickle_tempest/6577d3f1500aebcd300787bd5d96216b30aed379c811f5e83e888f897da4a3d5/strings) without running it?
# Solucion

```
affogato1-picoctf@webshell:~$ chmod +x strings 
affogato1-picoctf@webshell:~$ ./strings
Maybe try the 'strings' function? Take a look at the man page

affogato1-picoctf@webshell:~$ strings strings | grep pico
picoCTF{5tRIng5_1T_d6306c19}
```
### Flag: picoCTF{5tRIng5_1T_d6306c19}
# Notas
ELF es un formato para formato ejecutable y vinculable. Se utiliza para almacenar binarios, bibliotecas y volcados de núcleo en discos en sistemas basados en Linux y Unix.
# Referencias
https://medium.com/@ajmewal/basics-of-elf-executable-and-linkable-format-file-88a516877356