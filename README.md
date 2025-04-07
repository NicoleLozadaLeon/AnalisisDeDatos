# Proyecto de Análisis de Indicadores Socioeconómicos
# # 1. Introducción
# # # En un mundo cada vez más interconectado, la comprensión de los indicadores socioeconómicos a nivel global se vuelve esencial para la formulación de políticas efectivas y el desarrollo sostenible. Este proyecto, elaborado por Nicole Lozada Leon, explora diversas métricas que reflejan el estado económico y social de diferentes países, utilizando un enfoque basado en datos.

# # # A través de la recolección y análisis de información relevante, se busca identificar patrones y tendencias que informen decisiones estratégicas en el ámbito socioeconómico. Se emplean variadas técnicas de recolección de datos, incluyendo web scraping, acceso a APIs y el consumo de archivos planos. Las métricas clave incluyen:

# # # Densidad poblacional (Densidad P/Km²)
# # # Esperanza de vida (EV)
# # # Acceso a Internet
# # # Inflación
# # # Producto Interno Bruto (PIB) de 2023
# # # La información se clasifica por continente, asegurando una base sólida para el análisis posterior.

# # 2. Recolección de Datos
# # # La recolección de datos es fundamental para construir un conjunto de información sólido y confiable. Este proceso comenzó con la búsqueda de archivos planos relevantes, encontrando un CSV en Kaggle titulado “Google Country Information Dataset 2023”, creado por el Data Scientist Nidula Elgiriyewithana. Este conjunto de datos está disponible bajo la licencia “Attribution 4.0 International”.

# # # Se utilizó la columna de densidad poblacional por su integridad. La esperanza de vida se obtuvo de IndexMundi, y el PIB se consultó en la página del Fondo Monetario Internacional (FMI). Finalmente, se accedió a datos sobre acceso a Internet y la inflación a través de la API de Databank, utilizando la librería Deep Translator para asegurar la coherencia en los nombres de los países.

# # 3. Limpieza y Transformación
# # # La limpieza y transformación de datos son pasos críticos para garantizar la calidad del conjunto de información. Se priorizó el uso de columnas sin valores nulos. Se estandarizaron los nombres de los países, corrigiendo discrepancias manualmente y creando un diccionario que facilitó la integración de diferentes dataframes.

# # 4. Análisis Exploratorio de Datos (EDA)
# # # Se realizó un análisis exhaustivo de los indicadores socioeconómicos, obteniendo media, mediana y desviación estándar de las variables cuantitativas. Se generaron histogramas y diagramas de caja para identificar outliers. Se observó que Chad tiene una esperanza de vida por debajo de los 60 años, mientras que Japón se acerca a los 85 años, destacando disparidades significativas.

# # # Además, se analizó la matriz de correlación, encontrando una fuerte relación positiva entre el acceso a Internet y la esperanza de vida.

# # 5. Conclusiones
# # # El análisis ha revelado disparidades significativas en la esperanza de vida entre países. La correlación entre el acceso a Internet y la esperanza de vida sugiere que la tecnología puede influir en el bienestar de la población. La identificación de outliers permite un análisis más profundo de las causas subyacentes de estas desigualdades.

# # 6. Recomendaciones
# # # Se recomienda:

# # # Expansión del conjunto de datos para incluir más países.
