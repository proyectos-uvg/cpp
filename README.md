# Investigación de Lenguajes de Programación – Entrega #1  
## Lenguaje: C++

**Curso:** CC2016 – Algoritmos y Estructuras de Datos  
**Universidad:** Universidad del Valle de Guatemala  
**Semestre:** I – 2026  

---

## 📌 Descripción del proyecto

Este repositorio corresponde a la **Entrega #1 (Hola Mundo)** del proyecto de investigación de lenguajes de programación.  
El objetivo de esta entrega es instalar y configurar el ambiente de desarrollo del lenguaje seleccionado (**C++**), conocer su sintaxis básica y verificar su correcto funcionamiento mediante un programa sencillo.

---

## 🧠 Lenguaje seleccionado: C++

C++ es un lenguaje de programación **compilado y fuertemente tipado**, ampliamente utilizado en el desarrollo de software de alto rendimiento, sistemas operativos, videojuegos y aplicaciones donde la eficiencia es crítica.  
Es especialmente relevante para el estudio de **algoritmos y estructuras de datos**.

---

## 🌐 Sitio web oficial del lenguaje

- https://isocpp.org/

---

## 📚 Recursos para aprender C++

### Documentación
- https://en.cppreference.com/

### Tutoriales
- https://www.learncpp.com/
- https://www.cplusplus.com/doc/tutorial/

### Videos
- https://www.youtube.com/@TheCherno
- https://www.youtube.com/@freecodecamp

### Libros
- *Programming: Principles and Practice Using C++* – Bjarne Stroustrup  
- *C++ Primer* – Lippman, Lajoie, Moo  

---

## 🛠️ Ambiente de desarrollo

### Sistema operativo
- Windows (64 bits)

### Compilador
- GCC / g++ 15.2.0 (MinGW-w64)

### Herramienta utilizada: WinLibs

Se utilizó **WinLibs (MinGW-w64)** porque permite compilar C++ en Windows sin instalar Visual Studio, es portable, utiliza un compilador moderno (GCC) y emplea UCRT y POSIX threads para mejor compatibilidad con librerías modernas.

- https://www.winlibs.com/

---

## ⚙️ Instalación y configuración

1. Descargar WinLibs desde su sitio oficial.
2. Descomprimir el archivo.
3. Agregar la ruta `mingw64/bin` a la variable de entorno `PATH`.
4. Verificar la instalación:

## ▶️ Compilación y ejecución

### 📄 Archivo fuente
- `main.cpp`

### 🔧 Compilación
Desde la terminal, ubicándose en la carpeta del proyecto:

```bash
g++ main.cpp -o main
