# Pre-entrega Automation Testing - Brian Paez

## Propósito del Proyecto
Este proyecto consiste en la automatización de pruebas end-to-end (E2E) para la plataforma e-commerce [SauceDemo](https://www.saucedemo.com/), utilizando Python, Selenium WebDriver y Pytest. El objetivo es validar los flujos principales de la aplicación, como el inicio de sesión y la navegación.

## Tecnologías Utilizadas
- **Python** (Lenguaje de programación)
- **Pytest** (Framework de ejecucion de pruebas)
- **Selenium WebDriver** (Automatización de navegación web)
- **WebDriver Manager** (Gestión automática de drivers de navegador)
- **Pytest-HTML** (Generación de reportes de ejecución)

## Estructura del Proyecto
- tests/: Archivos de pruebas automatizadas (.py)
- utils/: Funciones auxiliares y utilidades reutilizables
- reports/: Reportes HTML generados tras la ejecución
- pytest.ini: Configuración de ejecución de Pytest
- .gitignore: Archivos y carpetas excluidos del control de versiones
- README.md: Documentación del proyecto

## Instalación de Dependencias
1. Clonar el repositorio:
git clone https://github.com/br1an17/pre-entrega-automation-testing-Brian-Paez.git

2. Acceder al directorio del proyecto:
cd pre-entrega-automation-testing-Brian-Paez

3. Instalar las librerías requeridas:
pip install pytest selenium webdriver-manager pytest-html

## Ejecución de Pruebas
Para ejecutar la suite completa de pruebas y generar automáticamente el reporte HTML en la carpeta reports/, ejecutá el siguiente comando en la terminal:

pytest

El resultado visual de la ejecución estará disponible en reports/reporte.html.