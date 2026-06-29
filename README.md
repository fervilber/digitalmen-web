# Digitalmen Web 🌐

Este repositorio contiene el motor de publicación y visualización web para la base de conocimiento **Digitalmen**, creada y mantenida por **F.VilBer**.

Puedes ver el contenido completo de mis notas en:
     <https://fervilber.github.io/digitalmen-web/>

## 🚀 Acerca del Proyecto

**Digitalmen Web** es la versión pública de un "segundo cerebro" estructurado en archivos Markdown. Utiliza el framework **Quartz** como motor de generación estática de alto rendimiento para ofrecer una interfaz fluida, rápida y totalmente optimizada para la lectura.

## 🛠️ Arquitectura de Despliegue

La sincronización de contenidos y la generación del sitio web se realizan de manera 100% automatizada a través de **GitHub Actions**:

1. **Origen de Datos (`digitalmen`)**: Repositorio privado que contiene las notas de Obsidian en Markdown sobre competencias digitales, IA, diseño 3D y más.
2. **Generador y Publicador (`digitalmen-web`)**: Este repositorio aloja el motor de renderizado y el tema visual.
3. **Automatización (CI/CD)**: Cada cambio en el repositorio de origen activa un flujo de trabajo que clona el motor, descarga las notas, compila el sitio con Quartz y lo despliega automáticamente en **GitHub Pages**.

---
*Desarrollado con ❤️ y tecnología estática para una lectura rápida y sin distracciones.*
