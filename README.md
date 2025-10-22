<img width="959" height="202" alt="image" src="https://github.com/user-attachments/assets/b533c9eb-46fa-4515-81cc-e2e5c5f9b9e6" />

🧪 Propósito del Proyecto

Este proyecto forma parte de la pre-entrega del curso de Testing Manual y Automatización (Clase 8). El objetivo es demostrar la capacidad para automatizar flujos básicos de navegación web utilizando Selenium WebDriver y Python, aplicando estrategias de localización, validaciones de estado y buenas prácticas de testing automatizado.

El sitio utilizado es https://www.saucedemo.com, una aplicación web demo diseñada para prácticas de QA.

🧰 Tecnologías Utilizadas

Python 3.10+

Selenium WebDriver → automatización de navegador

Pytest → estructura y ejecución de tests

webdriver-manager → manejo automático de ChromeDriver

pytest-html → generación de reportes en HTML

📁 Estructura del Proyecto
pre-entrega-automation-testing-facundo-almara/
├── README.md

├── requirements.txt

├── pytest.ini

├── tests/

│ ├── test_saucedemo.py

│ └── conftest.py

├── utils/

│ ├── driver_factory.py

│ └── pages.py

├── reports/

 └── reporte.html 
 


🧠 Casos de Prueba Implementados
1. Login Automatizado

Navega a saucedemo.com

Instalación
Asegúrate de tener Python 3.7 o superior instalado
Descarga el WebDriver correspondiente a tu navegador: selenium.dev
Clona este repositorio:
git clone https://github.com/FacuAi/Pre-entrega-Automation-Testing
Instala las dependencias:
 pip install selenium pytest pytest-html
🧠
test_login: Verifica acceso correcto a la página de inventario.
test_catalogo: Comprueba la presencia de productos, filtros y menú.
test_carrito: Valida que agregar un producto al carrito funcione correctamente.
Ejecución
Ejecuta las pruebas con:
pytest -v tests/test_saucedemo.py
Para generar un reporte HTML:
pytest tests/test_saucedemo.py -v --html=./reports/reporte.html
💡 Autor

Facundo Almara
Curso: Qa (Clase 8)
