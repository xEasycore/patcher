# patcher
Instrucciones

Requisitos: 1.Bajar Thor Patcher: thor.aeomin.net 2.Estar registrado en GitHub y ser colaborador del repositorio

Pasos:

Descomprimimos el Thor Patcher
Vamos a la carpeta ''Tools''
Abrimos Thor Generator
Conociendo Thor Generator:

El cuadro Output se refiere al directorio de salida del parche. Se guardará en el directorio indicado, con el nombre indicado, un archivo con extensión .thor

Tenemos dos opciones posibles: ''File'' para actualizar archivos de la carpeta raíz del RO (usualmente System) y ''Grf'' para actualizar el Grf, en este caso ''xdata.grf''. Debemos indicar el nombre xdata.grf para que Thor lo reconozca.

En input debemos seleccionar el o los archivos a parchar; deben encontrarse en el directorio correspondiente al Grf o System. Si quiero actualizar el grf, debería ser algo como data/luafiles514/lua files/skillinfoz/skilldesc.lub

En Compression Level seleccionamos High, para un alto nivel de compresión

Options. En este lado seleccionamos Acsii, SIEMPRE.

Nota 1: En el caso de querer actualizar algún archivo de la carpeta System, es lo mismo, salvo que Thor nos preguntará el directorio en el que el parche será lanzado. En este caso debemos seleccionar ''Other'', y ponemos /System

Nota 2: Para el caso de los GRF, luego de crear el .thor, debemos encriptarlo para que quede invisible dentro del grf. En este caso, debemos abrir el .thor con GRF-Editor. Lo encriptamos con la contraseña del Grf, y lo guardamos en un lugar diferente para posteriormente subirlo al repo.
