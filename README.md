# Trabajo Practico N°4 - Lenguaje Mini (Analizador Sintáctico / Parser con Bison) (Sin generador de código ni errores semánticos)
Cuarto Trabajo Practico Sintaxis y Semantica de los Lenguajes - Año 2020 - Curso K2053

## Integrantes
* Lucas Maspero               (Legajo 161542-7)
* Franco Nicolás Magne Colque (Legajo 168756-6)
* Natalia Gutiérrez           (Legajo 156549-7)

## Instalacion
* IDE: **Visual Studio Code**
* Descargar Archivos: "**git clone https://github.com/LucasMaspero/TPSyS4.git**"

## Ejecucion
1) Ubicarse en carpeta Resolucion: "**cd Resolucion**"
2) Ejecutar Flex: "**flex scanner.l**" (recordar hacerlo en la Máquina Virtual de Ubuntu en donde ya esta instalado **flex**)
3) Ejecutar Bison: "**bison parser.y**" (recordar hacerlo en la Máquina Virtual de Ubuntu en donde ya esta instalado **bison**)
4) Compilar: "**gcc -g -Wall \*.c -o tp4 -lfl**"
5) Ejecutar: "**tp4 < ../DatosDePrueba/entradaok.txt >./DatosDePrueba/salidaTP4.txt**"