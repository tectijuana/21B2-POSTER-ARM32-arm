# Sección de código MAKE / programas


Usar y complementar el Makefile, una excelente utilieria para agregarle a sus nuevas habilidares, 
recuerde que el formato de Makefile es sensible a tabulación.

![](/imagen/Make%20Templete%20Generico.png)

"programa" para montarlo en MAKE, UD. lo adapta y renombra a sus fines practicos.

------
Makefile

```make
# Makefile
all: programa
programa: programa.o
  ld -o $@ $+
programa.o : programa.s
  as -g -mfpu=vfpv2 -o $@ $<
clean:
 rm -vf programa *.o
```
