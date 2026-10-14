# Práctica 1 PMDM - Mi primera app Android: Recetario Yusito

**Autor:** José María Martín Martínez
**Módulo:** Programación Multimedia y Dispositivos Móviles

## Descripción del Proyecto
Aplicación nativa de Android que muestra la receta casera de una tortilla de patatas con queso. El proyecto está desarrollado en Java utilizando la plantilla *Empty Views Activity* y sirve como demostración práctica del manejo de layouts y la gestión de recursos externos en Android Studio.

## Requisitos Técnicos Implementados
Durante el desarrollo de esta práctica se han aplicado y validado los siguientes elementos obligatorios:

* **Textos e Internacionalización:** Centralización de todas las cadenas de texto en `strings.xml` y soporte multilenguaje (español e inglés) mediante el calificador de recursos `en`.
* **Arrays de datos:** Implementación de un `string-array` para listar los ingredientes dentro de un componente `Spinner`.
* **Diseño y Estilos:** 
  * Paleta de colores personalizada definida en `colors.xml`.
  * Estilos visuales propios aplicados a textos y botones, definidos en `themes.xml`.
* **Recursos Gráficos (`drawable` y `mipmap`):**
  * Integración de imagen de mapa de bits (`tortilla.png`).
  * Inserción de icono vectorial (`baseline_food_bank_24.xml`).
  * Creación de un icono de aplicación adaptativo (Image Asset) personalizado.
* **Layout (`activity_main.xml`):** Interfaz construida sin textos ni valores *hardcoded*, referenciando en todo momento los recursos externos creados (usando `@string`, `@color`, `@style`, `@array` y `@drawable`).
