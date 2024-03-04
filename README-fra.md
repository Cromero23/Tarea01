Para que ejecute el programa Hola mundo digite el siguiente comando
 nano
Abrira una archivo de texto para editar en el archivo agrege los sig.
#include <stdio.h>

int main() {
    printf("Salut Monde!!!\n");
    return 0;
}
luego guarde los cambios con el sig. nombre
prog-01-fra.c
para colocarlo en el compilador ejecute el siguiente comando
gcc prog-01-fra.c 
una vez que vea que no tiene errores, puede cambiar el nombre usando el sig. comando
gcc prog-01-fra.c -o prog-fra
una vez realizado el cambio solo es necesario ejecutar el comando
./prog-fra
