# Sistema de Gestión de Colmenas para Apicultores 🐝

Este proyecto es una aplicación de consola en Java diseñada para ayudar a los apicultores a gestionar eficientemente sus colmenas, abejas reinas, apicultores e inspecciones. Se aplican conceptos avanzados de programación orientada a objetos (POO), manejo de archivos, validaciones con expresiones regulares, concurrencia (hilos), recursividad y expresiones lambda.

## Características principales ✅

- 📦 Gestión de Colmenas: Agregar, listar, buscar, eliminar y actualizar colmenas.
- 🧑‍🌾 Gestión de Apicultores: Registrar, buscar y asociar apicultores a colmenas.
- 👑 Gestión de Abejas Reina: Control sobre edad, salud y productividad.
- 📋 Gestión de Inspecciones: Registro de inspecciones con fecha, resultados y acciones tomadas.
- 💾 Persistencia: Carga y guardado automático en archivos `.txt` y exportación a `.csv`.
- 🧮 Expresiones Regulares: Validación de datos como IDs y nombres.
- 🔁 Recursividad: Búsqueda en historial de inspecciones.
- 🧵 Hilos: Simulación de inspecciones concurrentes.
- 💡 Lambda: Reportes e informes filtrados.
- 🧭 Menú interactivo: Navegación clara desde consola.
- 🎓 Código profesional, limpio y modular.

## Estructura de paquetes 📁

```
com.apicultor.model     → Modelos de datos (Colmena, Apicultor, AbejaReina, Inspección)
com.apicultor.service   → Lógica de negocio (ColmenaService, ApicultorService, etc.)
com.apicultor.utils     → Manejo de archivos, validaciones y utilidades
com.apicultor.Main      → Menú principal
```

## Autor ✍️

**Aransy García**

## Uso 🚀

1. Clonar el repositorio o importar el ZIP en tu IDE (Eclipse recomendado).
2. Ejecutar la clase `Main.java` desde el paquete `com.apicultor`.
3. Interactuar con el sistema desde consola.

## Licencia 📄

Este proyecto está licenciado bajo los términos de la licencia MIT. Ver archivo `LICENSE.txt`.
