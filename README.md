# Biblioteca XML

Este proyecto contiene la descripción y validación de un documento XML que representa una biblioteca digital.  
Se implementa el modelo de datos con ejemplos de 5 libros, y se ha validado tanto con DTD como con XML Schema (XSD).

## Archivos del Proyecto

- **biblioteca.xml**: Documento XML principal.
- **biblioteca.dtd**: Definición de la estructura del XML usando DTD.
- **biblioteca.xsd**: Esquema XML para la validación con XSD.
- **README.md**: Este documento.

## Validación

Para validar el documento:
- **Con DTD:** Asegúrate de que el `biblioteca.dtd` esté en la misma carpeta que `biblioteca.xml`.  
- **Con XSD:** Comenta la línea del DTD en `biblioteca.xml` y usa la referencia al XSD.

## Capturas de Pantalla

(Incluye aquí imágenes que muestren la validación correcta en el editor o en herramientas online).

## Validación de Documentos XML

Se han validado dos archivos:
- **biblioteca.xml:** Documento con la estructura correcta, validado exitosamente contra el DTD (o XSD).
- **biblioteca_invalido.xml:** Documento con errores intencionales (p. ej., falta el elemento `<isbn>` en uno de los `<libro>`), lo que permitió comprobar que el esquema detecta las inconsistencias.

La validación se realizó utilizando Visual Studio Code con la extensión "XML Tools" y se verificó con la herramienta en línea [XMLValidation.com](https://www.xmlvalidation.com/).
