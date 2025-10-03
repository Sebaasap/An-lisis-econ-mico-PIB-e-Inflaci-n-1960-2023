# Análisis Económico: PIB per cápita e Inflación (1960–2023)

Este proyecto en **Python** descarga datos reales del **Banco Mundial** y compara dos indicadores en **Colombia, México y Estados Unidos**:

- **PIB per cápita (US$ corrientes)** → `NY.GDP.PCAP.CD`  
- **Inflación anual (%)** → `FP.CPI.TOTL.ZG`  

## Uso
1. Descargue este repositorio con el botón verde **Code → Download ZIP**.
2. Descomprima el archivo ZIP en su computador.
3. Abra el archivo `proyecto_economia.py` en su entorno de Python
4. Ingrese los años inicial y final (válidos entre 1960 y 2023).
5. El programa mostrará:
   - Una tabla con los primeros datos descargados
   - **Gráficos** comparativos de los tres países
   - **Estadísticas** (promedio, mediana, mínimo y máximo) usando NumPy

## Archivos
- `proyecto_economia.py`: código principal
- `requirements.txt`: lista de librerías necesarias

## Fuente de datos
- **Banco Mundial API**: datos oficiales de PIB per cápita e Inflación
