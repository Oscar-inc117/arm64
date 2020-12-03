# POR: Dominguez Ortiz Oscar Ivan
# No. Control: 18212174
# Archivo Makefile: Codigo que compila un programa definido.
# Fecha: 12/02/2020
# Materia: Lenguajez de interfaz.

# Makefile
all: holamundo
holamundo: holamundo.o  # enlazarlo para correrlo
	ld -o holamundo holamundo.o
holamundo.o: holamundo.s # compilarlo nos genera el .o
	as -g -o holamundo.o holamundo.s
clean:   # limpiar todo que no se ocupa como lo .o basura
	rm -vf holamundo *.o

