##hello wordl
Cuando nosotros deseamos invocar al programa, entonces el runtime entra en acción,
lee el assembly y crea para nosotros todo el entorno necesario. El runtime
empieza a leer las instrucciones CIL del assembly y conforme las va leyendo las
compila para el microprocesador de la computadora en la que corre el programa;
esto se conoce como JIT o compilación justo a tiempo. De esta manera conforme
se avanza en la ejecución del programa se va compilando; todo esto ocurre de
manera transparente para el usuario.