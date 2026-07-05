# Framework de Automatización de Pruebas Integradas - María Grillo

## 📌 Propósito del Proyecto
Este proyecto consiste en el desarrollo de un Framework de Automatización de Pruebas de extremo a extremo (E2E) robusto y mantenible. Está diseñado para validar flujos tanto de interfaz de usuario (UI) como de servicios web (API), garantizando la estabilidad operativa del software mediante la ejecución de suites de pruebas consistentes e independientes.

---

## 🛠️ Tecnologías Utilizadas
- **Python**: Lenguaje de programación principal para el diseño de scripts.
- **Pytest**: Framework de testing encargado de la recolección, aserciones y ejecución de la suite.
- **Selenium WebDriver**: Herramienta de automatización para interacciones de interfaz de usuario (UI) web.
- **Requests**: Biblioteca de comunicación HTTP para el consumo y validación de endpoints (API).
- **Git & GitHub**: Control de versiones y alojamiento remoto del repositorio.
- **Pytest-HTML**: Extensión para la generación automática de reportes visuales consolidados.
---

## 📁 Estructura del Proyecto

El framework sigue el patrón de diseño **Page Object Model (POM)** y está organizado de la siguiente manera:

* **`data/`**: Contiene los archivos de datos externos (`users.csv`, `products.json`) para la parametrización de las pruebas.
* **`page/`**: Clases del Page Object Model que contienen los localizadores y las interacciones con la interfaz de usuario.
* **`test/`**: Suites de pruebas automatizadas divididas por módulos (UI y API).
* **`utils/`**: Funciones auxiliares y herramientas reutilizables para el framework.
* **`logs/`**: Almacenamiento de los registros detallados generados durante la ejecución.
* **`reports/`**: Carpeta donde se compilan los reportes visuales de resultados.
* **`conftest.py`**: Configuración global de Pytest, fixtures del WebDriver de Selenium y gestión de capturas en caso de fallas.

---

## 🛠️ Instalación y Configuración

Para clonar este repositorio y configurar el entorno local, ejecutá los siguientes comandos en tu terminal de PowerShell:

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/Mgrillo348/proyecto-final-automation-maria-grillo.git](https://github.com/Mgrillo348/proyecto-final-automation-maria-grillo.git)
   cd proyecto-final-automation-testing-maria-grillo