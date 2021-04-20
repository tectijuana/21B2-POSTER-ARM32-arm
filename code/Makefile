
# Materia: Lenguajez de interfaz.
# Programador: ___
# Archivo Makefile: Código que compila los programa de ensamblador incluye limpieza para subir a GitHub.
# Fecha: ____

# Makefile
all: programa
programa: programa.o  # enlazarlo para correrlo	
	@echo "                                       _      _        "
	@echo "     /\                               | |    | |      " 
	@echo "    /  \    ___  ___   ___  _ __ ___  | |__  | | _   _ "
	@echo "   / /\ \  / __|/ __| / _ \| '_ ` _ \ | '_ \ | || | | |"
	@echo "  / ____ \ \__ \\__ \|  __/| | | | | || |_) || || |_| |"
	@echo " /_/    \_\|___/|___/ \___||_| |_| |_||_.__/ |_| \__, |"
	@echo "                                                  __/ |"
	@echo "                                                 |___/ "
	@echo "Linking file & executable..."
	ld -o $@ $+
programa.o: programa.s # compilarlo nos genera el .o
	@echo "Compiling file ..."
	as -g -mfpu=vfpv2 -o $@ $<
clean:   # limpiar todo que no se ocupa como lo .o basura
	@echo "Removing trash to upload to GitHub Classroom, teacher evaluate my progress ..."
	rm -vf first *.o
