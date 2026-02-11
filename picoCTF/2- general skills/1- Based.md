# Reto
# Descripcion
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337?

Additional details will be available after launching your challenge instance.
# Solucion

```
affogato1-picoctf@webshell:~$ nc fickle-tempest.picoctf.net 60432
Let us see how data is stored
container
Please give the 01100011 01101111 01101110 01110100 01100001 01101001 01101110 01100101 01110010 as a word...
you have 45 seconds.....

Input:
container
Please give me the  o156 o165 o162 o163 o145 as a word.
Input:
nurse
Please give me the 636f6c6f7261646f as a word.
Input:
colorado
You've beaten the challenge
Flag: picoCTF{learning_about_converting_values_bf1F59A2}
```

binario
https://gchq.github.io/CyberChef/#recipe=From_Binary('Space',8)&input=MDExMDAwMTEgMDExMDExMTEgMDExMDExMTAgMDExMTAxMDAgMDExMDAwMDEgMDExMDEwMDEgMDExMDExMTAgMDExMDAxMDEgMDExMTAwMTA

octal
https://gchq.github.io/CyberChef/#recipe=Find_/_Replace(%7B'option':'Regex','string':'o'%7D,'',true,false,true,false)From_Octal('Space')&input=bzE1NiBvMTY1IG8xNjIgbzE2MyBvMTQ1

hexadecimal
https://gchq.github.io/CyberChef/#recipe=From_Hex('None')&input=NjM2ZjZjNmY3MjYxNjQ2Zg
### Flag: picoCTF{learning_about_converting_values_bf1F59A2}
# Notas
Se utilizo cyberchef para cada palabra y conseguir el reto
# Referencias
