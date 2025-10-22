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

Ingresa credenciales válidas (standard_user / secret_sauce)

Verifica que el login fue exitoso comprobando la URL /inventory.html y el título Products

2. Verificación del Catálogo

Valida el título de la página de inventario

Verifica que existan productos visibles

Lista nombre y precio del primer producto

3. Interacción con el Carrito

Agrega el primer producto al carrito

Verifica que el contador del carrito se actualice

Accede al carrito y valida que el producto se haya agregado correctamente

📸 Evidencias y Reportes

Reporte HTML: reports/reporte.html

Capturas automáticas en caso de fallos: reports/FAIL_nombre_del_test.png

🧾 Buenas Prácticas Aplicadas

Page Object Model (POM) para separar la lógica de interacción con la UI.

Esperas explícitas para sincronizar correctamente con los elementos del DOM.

Fixtures de Pytest para inicializar y cerrar el navegador.

Capturas automáticas en caso de error.

Commits frecuentes y descriptivos.


💡 Autor

Facundo Almara
Curso: Qa (Clase 8)
