# Reto
## Descripcion
If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII?
### Solucion 1
- Usando cyberchef
- https://gchq.github.io/CyberChef/#recipe=From_Hex('0x')&input=MHg3MA
### Solucion 2 
- Usando python
```
	>>> int(0x70)
	112
	>>> chr(112)
	'p'
	>>> ord('p')
	112
	>>> 
```

### Flag: P
## Notas

## Referencias
- https://gchq.github.io/CyberChef/