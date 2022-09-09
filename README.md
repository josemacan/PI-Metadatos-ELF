# Comunicación desde Espacio de Usuario A Espacio de Kernel mediante Metadatos en Archivos ELF

Repositorio perteneciente al trabajo de Proyecto Integración llevado a cabo por [@josemacan](https://github.com/josemacan) y [@jukkanghost](https://github.com/jukkanghost)

## ELFBag

Plugins para insertar metadatos en el programa de usuario al compilar el código fuente del desarrollador.

- *CLANGPlugin*: plugin para la suite de compilación CLANG\LLVM. Permite realizar la inserción de datos al programa de usuario de forma transparente.
- *GCCPlugin*: idem anterior para la suite GCC.

Release [aquí](https://github.com/josemacan/ELFBag)

## Parche para FreeBSD 12.3

Desarrollo de parche de kernel de FreeBSD 12.3 para la detección, lectura y decodificación de ejecutables ELF con metadata insertada.

Release [aquí](https://github.com/josemacan/metadataFreeBSD_releng12.3)

## Parche para FreeBSD 13

Idem anterior para kernel de FreeBSD 13.

Release [aquí](https://github.com/josemacan/metadataFreeBSD_releng13)
