# Manipulación de Archivos en Java

Este repositorio contiene una colección de ejemplos y utilidades que demuestran cómo trabajar con las APIs de **Java I/O** y **NIO** para manejar archivos y directorios. Los ejemplos incluyen operaciones básicas como crear, leer, modificar y eliminar archivos y directorios, utilizando las clases `File`, `Files`, `Path` y `Paths`.

---

## Tabla de Contenidos
- [Descripción General](#descripción-general)
- [Requisitos](#requisitos)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Funciones Implementadas](#funciones-implementadas)
- [Contribuciones](#contribuciones)

---

## Descripción General
Este proyecto fue diseñado para explorar las funcionalidades de las APIs de Java relacionadas con la manipulación de archivos y directorios. Los ejemplos incluyen el uso de métodos para trabajar con:
- Creación y eliminación de directorios y archivos.
- Lectura y escritura de datos en archivos.
- Modificación de contenidos de archivos.
- Escaneo y listado de directorios.
- Uso de acceso aleatorio (`RandomAccessFile`) para manipular datos.

---

## Requisitos
1. **JDK 17 o superior**
2. Un IDE como **IntelliJ IDEA** o cualquier editor compatible con proyectos Java.
3. Gradle (opcional, si decides integrarlo).

---

## Estructura del Proyecto
```plaintext
ADAT_U1_File_Manipulation/
├── src/
│   └── com/proyecto/
│       ├── U1x01A_NewDir.java       # Crear un nuevo directorio
│       ├── U1x01B_NewDirScan.java   # Escanear un directorio
│       ├── U1x02A_NewFile.java      # Crear un nuevo archivo
│       ├── U1x02B_NewFileData.java  # Escribir datos en un archivo
│       ├── U1x03A_ReadFile.java     # Leer un archivo
│       ├── U1x04A_DeleteFile.java   # Eliminar un archivo
│       ├── U1x05A_UpdateFile.java   # Modificar el contenido de un archivo
│       ├── U1x06A_ListFile.java     # Listar archivos en un directorio
│       └── U1x07_RandomAccess.java  # Uso de RandomAccessFile
└── JavaStandalone.iml               # Archivo de configuración del proyecto
```

---

## Funciones Implementadas

### 1. `U1x01A_NewDir`
- **Descripción:** Crea un nuevo directorio especificado.
- **Uso:** Demuestra cómo usar `Paths` y `Files` para verificar la existencia de directorios y crearlos si no existen.

### 2. `U1x01B_NewDirScan`
- **Descripción:** Escanea un directorio y lista los archivos y subdirectorios.
- **Uso:** Utiliza la clase `Files` para iterar sobre el contenido de un directorio.

### 3. `U1x02A_NewFile`
- **Descripción:** Crea un nuevo archivo.
- **Uso:** Explora el uso de `Files.createFile()` para la creación de archivos.

### 4. `U1x02B_NewFileData`
- **Descripción:** Escribe datos en un archivo.
- **Uso:** Emplea `Files.write()` para escribir contenido en un archivo de forma sencilla.

### 5. `U1x03A_ReadFile`
- **Descripción:** Lee el contenido de un archivo.
- **Uso:** Utiliza `Files.readAllLines()` para leer líneas de texto desde un archivo.

### 6. `U1x04A_DeleteFile`
- **Descripción:** Elimina un archivo.
- **Uso:** Implementa `Files.delete()` para manejar la eliminación de archivos.

### 7. `U1x05A_UpdateFile`
- **Descripción:** Modifica el contenido de un archivo existente.
- **Uso:** Mezcla lectura y escritura para actualizar archivos existentes.

### 8. `U1x06A_ListFile`
- **Descripción:** Lista los archivos y carpetas de un directorio.
- **Uso:** Usa `Files.newDirectoryStream()` para recorrer el contenido de un directorio.

### 9. `U1x07_RandomAccess`
- **Descripción:** Manipula datos en archivos utilizando acceso aleatorio.
- **Uso:** Utiliza la clase `RandomAccessFile` para leer y escribir en posiciones específicas dentro de un archivo.



## Contribuciones
¡Las contribuciones son bienvenidas! Si deseas añadir nuevas funcionalidades o mejorar el código existente, no dudes en crear un **pull request** o abrir un **issue** en el repositorio.

---

¡Gracias por visitar este proyecto! 🚀