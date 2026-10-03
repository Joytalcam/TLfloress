# TLflores

🌸 Clasificador de Flores con Transfer Learning
¡Bienvenido/a a TLfloress! Una aplicación web interactiva desarrollada en Python con Streamlit y TensorFlow que permite utilizar el poder del Aprendizaje por Transferencia (Transfer Learning) para identificar especies de flores mediante visión artificial.
Este repositorio contiene la interfaz gráfica que permite al usuario cargar su propio modelo previamente entrenado y sus etiquetas para realizar predicciones en tiempo real de forma dinámica.

🚀 Documentación y Portafolio Profesional
👉 (https://tlfloress-prueba.readthedocs.io/es/latest/) 🚀

🌻 Características Principales
• Carga Dinámica de Modelos: El sistema no requiere que el modelo esté pre-cargado en el servidor. Permite subir los archivos flower_model.keras y class_names.json directamente desde la interfaz gráfica.
• Predicciones en Tiempo Real: Procesa imágenes cargadas por el usuario (JPG, PNG, WEBP), redimensionándolas automáticamente a 224x224 píxeles para ser compatibles con el motor neuronal.
• Visualización de Probabilidades: Muestra un desglose gráfico interactivo mediante barras de progreso con los niveles de certeza (score) para cada una de las clases entrenadas.
• Interfaz Moderna y Fluida: Diseñada con componentes nativos de Streamlit y estilos CSS personalizados para ofrecer una experiencia limpia y responsiva.

⚙️ ¿Cómo funciona por dentro? (Detalle Técnico)
El motor de predicción se apoya en técnicas modernas de Deep Learning y Ciencia de Datos:
1. MobileNetV2: Se utiliza esta arquitectura de red neuronal liviana y altamente eficiente, ideal para dispositivos móviles y aplicaciones web rápidas.
2. Extractor de Características: Se congelan las capas base pre-entrenadas con millones de imágenes (ImageNet) y se añade una cabecera personalizada para clasificar específicamente especies de flores.
3. Especies soportadas originalmente: Margarita (🌼), Diente de León (🌱), Rosa (🌹), Girasol (🌻) y Tulipán (🌷).

📌 Estructura del Repositorio
• app_flores.py : Script principal que inicializa la interfaz de Streamlit, gestiona los archivos temporales en memoria y ejecuta las inferencias del modelo de TensorFlow.
• requirements.txt : Archivo de configuración que contiene las dependencias exactas y librerías necesarias para replicar el entorno de ejecución.

🛠️ Instalación y Uso Local
Para clonar y ejecutar este clasificador en tu entorno local, sigue estos sencillos pasos:
1. Clonar el repositorio
bash
git clone https://github.com
cd tlfloress
Use code with caution.

2. Instalar dependencias
Asegúrate de tener Python instalado y ejecuta en tu terminal:
bash
pip install streamlit tensorflow pillow numpy
Use code with caution.
(O de manera equivalente si utilizas el archivo de dependencias: pip install -r requirements.txt)

3. Iniciar la aplicación
Ejecuta el servidor local de Streamlit:
bash
streamlit run app_flores.py
Use code with caution.
Una vez ejecutado, abre tu navegador web en la dirección local indicada (normalmente http://localhost:8501).

🎯 Instrucciones de Uso en la App
1. Paso 1: Sube el archivo de tu modelo entrenado (flower_model.keras o .h5) y el archivo JSON con los nombres de tus clases (class_names.json).
2. Paso 2: Una vez que la interfaz confirme que el modelo está cargado con éxito, se habilitará la zona de carga de imágenes.
3. Paso 3: Sube una fotografía de una flor y observa el cuadro de resultados con el veredicto del modelo y su porcentaje de confianza.

📄 Licencia
Este proyecto se distribuye bajo la licencia MIT. Siéntete libre de usarlo, modificarlo y adaptarlo a tus necesidades.
