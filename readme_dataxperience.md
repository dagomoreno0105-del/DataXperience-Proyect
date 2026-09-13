# 🎬 DataXperience: Predicción del Éxito de Películas

## 📝 Descripción del Proyecto
Este repositorio contiene el proyecto desarrollado para **DataXperience**. El objetivo principal de este análisis es construir un modelo predictivo capaz de estimar el éxito de una película (medido a través de sus ingresos de taquilla y/o calificación del público) utilizando características fundamentales como el presupuesto, género, director, elenco y fecha de lanzamiento. 

A través del análisis exploratorio de datos (EDA) y la implementación de algoritmos de Machine Learning, buscamos identificar qué factores tienen el mayor impacto en el rendimiento comercial de una producción cinematográfica.

## 🗂 Estructura del Repositorio

El proyecto está organizado de la siguiente manera para facilitar su revisión y reproducibilidad:

```text
├── 📁 src/                 # Código fuente y scripts
│   ├── 📓 EDA_y_Modelos.ipynb # Jupyter Notebook con la limpieza de datos y entrenamiento
│   └── 🐍 utils.py            # Funciones auxiliares de procesamiento
├── 📁 docs/                # Documentación
│   └── 📄 Informe_Final.pdf   # Informe técnico detallado (metodología y hallazgos)
├── 📁 presentation/        # Presentación del proyecto
│   └── 📊 Pitch_Deck.pdf      # Diapositivas con el resumen ejecutivo y de negocio
├── 📁 data/                # Directorio para los datasets (originales y procesados)
└── 📄 README.md            # Este archivo
```

## ⚙️ Requerimientos y Dependencias

Para ejecutar el código de este repositorio, es necesario contar con **Python 3.8 o superior**. Las principales librerías utilizadas en este proyecto son:

* `pandas` - Para la manipulación y análisis de datos.
* `numpy` - Para operaciones numéricas.
* `matplotlib` & `seaborn` - Para la visualización de datos.
* `scikit-learn` - Para el preprocesamiento y construcción de modelos predictivos.
* `xgboost` / `lightgbm` - [Opcional: Especifica si usaste modelos avanzados de ensamble].

Puedes instalar todas las dependencias necesarias ejecutando el siguiente comando en tu terminal:

```bash
pip install -r requirements.txt
```

*(Nota: Asegúrate de tener los archivos CSV correspondientes en la carpeta `data/` antes de ejecutar el notebook).*

## 💡 Conclusiones Breves

Tras finalizar el análisis y el modelado, destacamos los siguientes hallazgos:

1. **Predictores más fuertes:** El presupuesto de producción y la popularidad previa del director/elenco principal mostraron la mayor correlación con los ingresos de taquilla.
2. **Impacto temporal:** Las películas lanzadas en [Mencionar época, ej. verano o fin de año] mostraron sistemáticamente un mayor rendimiento comercial frente al resto del año.
3. **Rendimiento del modelo:** El modelo final ([Nombre del Modelo, ej. Random Forest Regressor]) logró predecir el éxito con una precisión del `[X]%` (o un R² de `[X]`), demostrando que es posible estimar la viabilidad financiera de un proyecto cinematográfico en sus etapas iniciales.

---
*Desarrollado por **[Tu Nombre / Nombre de tu Equipo]** para DataXperience.*