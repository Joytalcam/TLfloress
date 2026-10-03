# 🌸 TLfloress: IA al Alcance de Todos

¡Bienvenido/a al portal oficial del proyecto **TLfloress**! Una herramienta práctica de visión artificial diseñada para identificar flores y plantas de manera instantánea mediante una simple fotografía.

---

# 🌻 ¿Qué es y para qué sirve?

¿Alguna vez te has encontrado con una flor hermosa en el campo, en el jardín o en un cultivo y te has preguntado qué especie es? 

**TLfloress** resuelve esto en segundos. Solo necesitas subir una foto desde tu celular o computador, y la aplicación analizará los pétalos, colores y formas para decirte exactamente de qué flor se trata, mostrando su nombre y el nivel de certeza del análisis.

## 🌼 Especies que reconoce actualmente:
* **Margarita** (*Daisy*) 🌼
* **Diente de León** (*Dandelion*) 🌱
* **Rosa** (*Roses*) 🌹
* **Girasol** (*Sunflowers*) 🌻
* **Tulipán** (*Tulips*) 🌷

---

# ⚙️ ¿Cómo funciona por dentro? (Detalle Técnico)

Este proyecto demuestra la aplicación práctica de técnicas modernas de **Deep Learning** y **Ciencia de Datos**:

* **Transfer Learning (Aprendizaje por Transferencia):** Se apoya en la arquitectura **MobileNetV2**, una red neuronal liviana y eficiente previamente entrenada con millones de imágenes.
* **Entrenamiento a la medida:** El modelo fue ajustado específicamente con miles de imágenes de flores para reconocer con alta precisión las características únicas de cada especie.
* **Interfaz Interactiva:** Desarrollada en **Python** utilizando **Streamlit**, ofreciendo una experiencia visual fluida, moderna y accesible directamente desde el navegador.

---

# 📌 Contenido del Repositorio

* **`app_flores.py`**: Script principal que alimenta la interfaz gráfica y ejecuta el motor de predicción neuronal.
* **`requirements.txt`**: Archivo de configuración con las dependencias necesarias (`tensorflow`, `streamlit`, `pillow`, `numpy`) para replicar o desplegar el entorno fácilmente.

---

> *Un proyecto que une la ingeniería, la analítica de datos y la sencillez para llevar la tecnología directo a la práctica.* 🚀
