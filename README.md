# Descripción de la Arquitectura de Software (BlueLotus System)

Este repositorio contiene la documentación oficial de la **Arquitectura del Sistema de Reservaciones de Habitaciones para una Cadena Hotelera (BlueLotus System)**, desarrollada como parte de la experiencia educativa de Diseño de Software.

La documentación sigue un enfoque ***docs-as-code***, lo que permite mantener la trazabilidad, consistencia y automatización del ciclo de vida de la documentación arquitectónica.

## 🎯 Objetivo
Aprender a documentar y gestionar la arquitectura de software aplicando prácticas profesionales de la industria:
- Uso de texto plano con **AsciiDoc + Asciidoctor** para mantener la documentación versionable y legible.
- Control de versiones con **Git y GitHub**, siguiendo flujos de trabajo colaborativos.
- **Integración continua (CI/CD)** para generar automáticamente las salidas HTML y PDF.
- Inclusión de diagramas arquitectónicos creados en ***Enterprise Architect (EA)***, exportados como imágenes PNG.
- Trazabilidad entre requerimientos, decisiones arquitectónicas y vistas del sistema.

## 👥 Equipo de Trabajo
Proyecto académico para la experiencia educativa de **Diseño de Software**, elaborado por los siguientes integrantes:
- Rodrigo Ivan Ahumada Rodríguez
- Abraham Cano Ramírez
- Mauricio Noriega Delgado

## 🧱 Estructura del proyecto
- docs/          → Archivos fuente de documentación en AsciiDoc
- images/        → Diagramas exportados desde Enterprise Architect
- build/         → Salida generada en HTML y PDF (ignorada en Git)

## 📘 Contenido del Documento Arquitectónico
La documentación completa incluye:
- Visión y objetivos del sistema
- Requisitos funcionales y de calidad
- Casos de uso y actores
- Modelo de conceptos de negocio
- Vistas arquitectónicas (4+1)
- Restricciones y decisiones arquitectónicas
- Conclusiones y consideraciones de implementación

## ⚙️ Requisitos técnicos
Para compilar y visualizar correctamente la documentación:
- **Ruby** (con Asciidoctor y Asciidoctor PDF instalados).
- **Visual Studio Code** con el plugin [AsciiDoc by Asciidoctor].

## 🧩 Compilación local (bash)
Ejecutar en la raíz del repositorio:
- ***Generar versión HTML:***
```bash
asciidoctor -D build docs/index.adoc
```
- ***Generar versión PDF:***
```bash
asciidoctor-pdf -o build/index.pdf docs/index.adoc
```
