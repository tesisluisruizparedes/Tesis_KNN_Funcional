📘 Tesis Doctoral: Predicción de Quiebra Empresarial con k-NN Funcional  
Este repositorio contiene todos los scripts necesarios para reproducir la metodología, evaluación y comparación del modelo funcional k-NN propuesto en la tesis doctoral, con énfasis en su interpretabilidad y competitividad frente a modelos tradicionales y avanzados.

⚙️ Estructura del Repositorio  
Tesis_KNN_Funcional/  
├── Datos/                      # Contiene la base funcional mínima 8_  
├── scripts/                   # Modelo k-NN funcional base y extendido  
├── scripts_comparativos/     # Modelos tradicionales, avanzados y secuenciales  
├── README.md  
├── requirements.txt  
└── .gitignore  

▶️ Ejecutar modelo funcional (Google Colab)  
Cada botón abre el notebook correspondiente:

| Notebook | Abrir en Colab |
|----------|----------------|
| 7_Analisis_Exploratorio.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/07_7_Analisis_Exploratorio.ipynb) |
| 8_Construccion_base_funcional.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/08_8_Construccion_base_funcional.ipynb) |
| 9_Mod_Pro_Parte_1_Optimizacion.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/09_9_Mod_Pro_Parte_1_Optimizacion.ipynb) |
| 10_Mod_Pro_Parte2_Distancias.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/10_10_Mod_Pro_Parte2_Distancias.ipynb) |
| 11_Mod_Pro_Parte3_ejecucion.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/11_11_Mod_Pro_Parte3_ejecucion.ipynb) |
| 12_Mod_Pro_Parte3_Robustez.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/12_12_Mod_Pro_Parte3_Robustez.ipynb) |



📌 Versión extendida del modelo funcional (con categóricas y temporales)
Incluye variables categóricas y temporales en la métrica de distancia. Disponible en los siguientes notebooks:  


| Notebook | Abrir en Colab |
|----------|----------------|
| 20_Mod_Pro_Mof_Parte_1(Optimizacion).ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/20_Mod_Pro_Mof_Parte_1(Optimizacion).ipynb) |
| 21_Mod_Pro_Modi_Parte_2(Distancias).ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/21_Mod_Pro_Modi_Parte_2(Distancias).ipynb) |
| 22_Mod_Pro_Modi_Parte3(Ejecución).ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/22_Mod_Pro_Modi_Parte3(Ejecución).ipynb) |
| 23_Mod_Pro_mModi_Parte4(Robustez).ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tesisluisruizparedes/Tesis_KNN_Funcional/blob/main/scripts/23_Mod_Pro_mModi_Parte4(Robustez).ipynb) |

📁 Requisitos de datos en Google Drive  
Todos los notebooks están configurados para leer archivos desde:  



/content/drive/MyDrive/Datos/
Asegurarse de tener una carpeta llamada Datos/ directamente en MyDrive/
Colocar dentro al menos el siguiente archivo:
6_Base_Modelos_Predictivos.parquet
⚠️ Sin esta estructura, los notebooks no podrán cargar los datos correctamente y producirán error de archivo no encontrado.


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
