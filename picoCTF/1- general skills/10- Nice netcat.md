# Reto
## Descripcion
There is a nice program that you can talk to by using this command in a shell:

Additional details will be available after launching your challenge instance.
## Solucion

```
affogato1-picoctf@webshell:~$ nc wily-courier.picoctf.net 50660
112 105 99 111 67 84 70 123 103 48 48 100 95 107 49 116 116 121 33 95 110 49 99 51 95 107 49 116 116 121 33 95 101 57 99 56 53 125 10
```
https://gchq.github.io/CyberChef/#recipe=From_Charcode('Space',10)&input=MTEyIA0KMTA1IA0KOTkgDQoxMTEgDQo2NyANCjg0IA0KNzAgDQoxMjMgDQoxMDMgDQo0OCANCjQ4IA0KMTAwIA0KOTUgDQoxMDcgDQo0OSANCjExNiANCjExNiANCjEyMSANCjMzIA0KOTUgDQoxMTAgDQo0OSANCjk5IA0KNTEgDQo5NSANCjEwNyANCjQ5IA0KMTE2IA0KMTE2IA0KMTIxIA0KMzMgDQo5NSANCjEwMSANCjU3IA0KOTkgDQo1NiANCjUzIA0KMTI1IA0KMTAg&ieol=CRLF
### Flag: picoCTF{g00d_k1tty!_n1c3_k1tty!_e9c85}
## Notas
Esta en ascii y se utilizo cyberchef para decodificar
## Referencias