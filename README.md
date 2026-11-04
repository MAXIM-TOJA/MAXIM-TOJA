# Hola, soy Maxim Toja 👋

Desarrollo aplicaciones de escritorio en **Python** orientadas a resolver problemas concretos de talleres, laboratorios y aficionados a la electrónica.

## Proyectos

### 📦 Inventario de componentes electrónicos

Aplicación de escritorio **portátil y sin servidor** para llevar el inventario de componentes electrónicos: qué hay, dónde está, cuánto vale, con qué documentación y cómo se etiqueta. Funciona desde una sola carpeta (incluso desde un pendrive), sin instalación ni conexión a internet.

**Funcionalidades principales**

- Clasificación en cuatro niveles (Tipo › Categoría › Subcategoría › Ítem) con parámetros técnicos heredados.
- Documentación por componente: imágenes, datasheets, tutoriales y esquemas, almacenados una sola vez por huella **SHA-256**.
- Visor de PDF integrado con selección de texto, recorte de regiones y **OCR** opcional (Tesseract).
- Valorización del **capital en existencia** con exportación a Excel.
- **Etiquetas en PDF con código QR** a medida de la hoja.

Hay dos ediciones equivalentes:

| Edición | Interfaz | Motor PDF | Repositorio |
|---|---|---|---|
| PySide6 | PySide6 (LGPL) | pypdfium2 | [inventario-componentes-pyside6](https://github.com/MAXIM-TOJA/inventario-componentes-pyside6) |
| PyQt5 | PyQt5 | PyMuPDF | [inventario-componentes-pyqt5](https://github.com/MAXIM-TOJA/inventario-componentes-pyqt5) |

## Tecnologías

Python · PySide6 / PyQt5 · SQLite · pypdfium2 / PyMuPDF · ReportLab · Tesseract OCR · openpyxl · PyInstaller

## Contacto

<!-- Agregá aquí tu correo, LinkedIn u otro medio de contacto si querés. -->

🌐 [maxim-toja.github.io](https://maxim-toja.github.io)
