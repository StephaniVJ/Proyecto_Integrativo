
# 💤 Análisis de la vulnerabilidad del sistema de salud en México: Cobertura y crecimiento poblacional**

Este proyecto implementa técnicas de agrupamiento (clustering)  para identificar patrones de vulnerabilidad estructural a nivel estatal partiendo de razones de salud poblacional y 
Cobertura Universal de Salud (CUS).

---
# 📚Estructura del repositorio
Carpetas:
1.DataFrames:[https://github.com/StephaniVJ/Proyecto_Integrativo/tree/main/DataFrames%20Generado)
      - DataFrame resultante de la clusterización de los datos 
2.Datos Camas:  [https://github.com/StephaniVJ/Proyecto_Integrativo/tree/main/Datos_Camas)
     - Archivo zip con los datos historicos(2002) de camas censables por entidad federativa 

3.Datos Médico:  [https://github.com/StephaniVJ/Proyecto_Integrativo/tree/main/Datos_M%C3%A9dicos)
     - Archivo zip con los datos historicos(2002) de médicos generales, especialistas y odontólogos por entidad federativa 
4.Graficos:  [https://github.com/StephaniVJ/Proyecto_Integrativo/tree/main/Gr%C3%A1ficos)
    - Imágenes relacionadas con la implementación del método K-means: Método del codo  e índice de silueta 
    - Visualización de clusters
    - Visualización del Índice de Cobertura Hospitalaria y del Índice de Cobertura Médica por entidad federativa
5.NoteBook:[https://github.com/StephaniVJ/Proyecto_Integrativo/tree/main/Notebook)
    - Código base
  
    
  
  - Readme.md
---
## 📊 Objetivo del Proyecto

  - Evaluar el grado de vulnerabilidad estructural del sistema de salud en las entidades federativas de México en función
  - del crecimiento de la población y la evolución de la infraestructura médica y hospitalaria entre 2002 y 2022.
---
## 🤖 Modelos Utilizado
Clusterig por K-means



---
## 📈 Resultados
El modelo identificó tres clusters:

	-Cluster 0: Estados con alta cobertura estructural o baja vulnerabilidad, ambos índices positivos.
	-Cluster 1: Estados con alta vulnerabilidad estructural, ambos índices negativos.
	-Cluster 2: Estados con riesgo parcial, uno de los índices positivo y otro negativo.

Cada estado fue asignado a uno de los tres clusters con base en su desempeño relativo.
La segmentación permite priorizar políticas públicas orientadas a reducir la desigualdad estructural entre regiones.

---
## 📑 Informe
Consulta el informe completo en formato PDF dentro del repositorio:
📎 report.pdf

Incluye:

* Descripción del problema médico

*Objetivo

* Análisis exploratorio

* Métpodología

* Conclusiones
  
---
## ⚙️ Requisitos
Instala las dependencias con:

```bash
pip install -r requirements.txt

# Puedes ejecutar el proyecto clonando este repositorio y abriendo el notebooks del código base. Tambien deberas descargar los archivos zip
correspondientes al histórico de datos de camas y médicos:
git clone (https://github.com/StephaniVJ/Proyecto_Integrativo)
cd Proyecto_Integrativo/Notebook
jupyter notebook Proyecto_Integrativo_Sistema de Salud_Vulnerabilidad_StephaniVJ.ipynb # Código base

```

Licencia
Este proyecto se distribuye bajo la licencia MIT. Puedes modificarlo y reutilizarlo libremente para fines educativos o personales.
