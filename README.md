
# 📘 Tesis Doctoral: Predicción de Quiebra Empresarial con k-NN Funcional

Este repositorio contiene todos los scripts necesarios para reproducir la metodología, evaluación y comparación del modelo funcional k-NN propuesto en la tesis doctoral, con énfasis en su interpretabilidad y competitividad frente a modelos tradicionales y avanzados.

---

## ⚙️ Estructura del Repositorio

```
Tesis_KNN_Funcional/
├── Datos/                      # Contiene solo la base limpia 6_
├── scripts/                   # Modelo k-NN funcional optimizado
├── scripts_comparativos/     # Modelos tradicionales, avanzados y secuenciales
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ▶️ Ejecutar modelo funcional (Google Colab)

Cada botón abre el notebook correspondiente:

- [![07](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/07_Analisis_Exploratorio.ipynb) `07_Analisis_Exploratorio.ipynb`
- [![08](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/08_Construccion_base_funcional.ipynb) `08_Construccion_base_funcional.ipynb`
- [![09](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/09_Mod_Pro_Parte_1_Optimizacion.ipynb) `09_Mod_Pro_Parte_1_Optimizacion.ipynb`
- [![10](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/10_Mod_Pro_Parte2_Distancias.ipynb) `10_Mod_Pro_Parte2_Distancias.ipynb`
- [![11](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/11_Mod_Pro_Parte3_ejecucion.ipynb) `11_Mod_Pro_Parte3_ejecucion.ipynb`
- [![12](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/12_Mod_Pro_Parte3_Robustez.ipynb) `12_Mod_Pro_Parte3_Robustez.ipynb`

---

## 🧪 Comparación con otros modelos (`scripts_comparativos/`)

Incluye notebooks con:

- Regresión Logística y Probit
- k-NN clásico
- Random Forest y XGBoost
- LightGBM y CatBoost
- LSTM, BiLSTM, CNN+LSTM
- SMOTE, Optuna y Stacking híbrido

⚠️ No se incluyen botones Colab aquí para evitar sobrecarga visual. Los notebooks pueden abrirse directamente desde la carpeta `scripts_comparativos/`.

---

## 📥 Requisitos

Instala las dependencias ejecutando:

```bash
pip install -r requirements.txt
```

---

## 📌 Notas importantes

- Este repositorio parte desde la base `6_Base_Modelos_Predictivos.parquet`.
- Los datos originales no están incluidos por tamaño (>1.4GB).
- Todos los notebooks son reproducibles en Colab.
