# Tachame la Lista! 

**Tachame la Lista!** es una aplicación de gestión de tareas (*to-do list*) sencilla, ligera y funcional, desarrollada en **Gambas3**.

## Características Principales

- **Gestión Intuitiva:** Agrega, marca y elimina tareas con facilidad.
- **Base de Datos:** Almacenamiento local mediante **SQLite3**, garantizando la integridad de tus datos.
- **Estados de Tarea:**
  - **Completado:** Marca tus logros con un simple clic.
  - **Importante (Resaltado):** Prioriza tareas críticas para que no pasen desapercibidas.
- **Panel de Detalles:** Cada tarea puede incluir una descripción extensa que se visualiza en un panel lateral dedicado.
- **Interactividad Sonora:** Reproducción de sonidos al completar tareas o limpiar la lista, brindando una experiencia más dinámica. (¿A quien no le gusta tachar ítems de una lista? xD)
- **Integración con el Sistema:**
  - **Atajos de Teclado:** Usa `Ctrl+A` para agregar tareas rápidamente.
- **Actualizaciones Automáticas:** Sistema integrado para buscar nuevas versiones directamente desde el repositorio oficial.

## Requisitos del Sistema

Para ejecutar o compilar este proyecto, necesitas:

- **Gambas 3.15** o superior.
- Componentes requeridos: `gb.db.sqlite3`, `gb.image`, `gb.gui.qt`, `gb.sdl2.audio`, `gb.gui.trayicon`.

## Estructura de la Base de Datos

La información se gestiona en una tabla llamada `datos` con los siguientes campos:

1.  **ID**: Identificador único.
2.  **Completado**: Booleano para el estado de la tarea.
3.  **Título**: Nombre principal de la tarea.
4.  **Contenido**: Descripción detallada opcional.
5.  **Resaltado**: Booleano para marcar tareas como importantes.

## Novedades de la Versión 0.7.x

- **Migración de Base de Datos:** Se ha actualizado el esquema de la base de datos a una versión superior para mejorar el rendimiento y la escalabilidad.
- **Compatibilidad Garantizada:** El sistema detecta automáticamente bases de datos de versiones anteriores (0.6.x y menores) y realiza una migración transparente de los datos, asegurando que no pierdas tu información al actualizar.
- **Refactorización de Código:** Limpieza y optimización de los módulos de base de datos y la interfaz de usuario.
- **Correcciones de Errores:** Se han corregido diversos fallos menores reportados en la serie 0.6.x.

## Instalación y Uso

1.  Clona el repositorio o descarga el código fuente.
2.  Abre el proyecto con el IDE de **Gambas3**.
3.  Presiona `F5` para ejecutar o genera el ejecutable desde el menú `Proyecto -> Crear -> Ejecutable...`.

**También se pueden descargar paquetes de instalación** -> *Releases*

---

## Contribuciones y Soporte

Este proyecto es de código abierto. Si encuentras un error o tienes una sugerencia, ¡no dudes en abrir un issue!

Puedes encontrar más información y otros proyectos en mi blog:  
🌐 [The Nerdy Apprentice](https://thenerdyapprentice.blogspot.com/)

Si te gusta mi trabajo, puedes apoyarme invitándome un café:

[![Invitame un café en cafecito.app](https://cdn.cafecito.app/imgs/buttons/button_1.svg)](https://cafecito.app/thenerdyapprentice)
