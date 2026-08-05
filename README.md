# 🪙 Conociendo las Monedas del Mundo: API, Web Scraping y Parsing de PDF

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MoisesNb7/conociendo-monedas-del-mundo/blob/main/conociendo_monedas_del_mundo.ipynb)

## 📌 Descripción del Proyecto
Se demuestra el uso de múltiples técnicas de extracción de datos en Python para compilar y validar una lista internacional de divisas (código ISO de 3 caracteres y nombre). 

Para garantizar la precisión de los datos, la información se consume de tres fuentes heterogéneas y se procesa para encontrar los elementos comunes validados en todas ellas.

---

## 🎯 Objetivos y Habilidades Demostradas
- **Consumo de APIs REST:** Peticiones HTTP a la API pública de Coinbase mediante la librería `requests`.
- **Web Scraping:** Parseo de tablas HTML en Wikipedia utilizando `BeautifulSoup`, limpiando referencias y notas al pie entre corchetes mediante expresiones regulares (`re`).
- **Parsing de PDF:** Extracción automatizada de texto plano desde documentos PDF no estructurados utilizando `tabula`.
- **Limpieza y Procesamiento de Datos:** Normalización de cadenas a minúsculas, eliminación de ruido sintáctico y uso de estructuras de datos tipo `set` (intersecciones) para determinar consistencia entre fuentes.

---

## 🛠️ Tecnologías Utilizadas
- **Lenguaje:** Python 3.x
- **Librerías Principales:** `requests`, `beautifulsoup4`, `tabula`, `re` (RegEx)
- **Entorno:** Google Colab / Jupyter Notebook

---
👤 **Autor:** Moisés Navarrete Bautista  
📂 **LinkedIn:** [linkedin.com/in/moisesnavarretebautista](https://www.linkedin.com/in/moisesnavarretebautista/)
