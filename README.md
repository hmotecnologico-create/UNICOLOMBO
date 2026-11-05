# Materiales de análisis de datos · Diplomado y electivas

Datasets, cuadernos de laboratorio y guías para practicar **calidad de datos, análisis exploratorio (EDA) y Power BI** con casos empresariales.

> Autor: **Heyder Medrano Olier** · Materiales usados en el Diplomado en Análisis de Datos y las electivas de UNICOLOMBO (2026). La institución se menciona como contexto académico.

## Cómo usarlos

1. Abre el cuaderno del laboratorio en Google Colab. Para eso, en GitHub abre el `.ipynb` y cambia `github.com` por `githubtocolab.com` en la dirección.
2. Los CSV se leen directo desde su enlace **Raw** de GitHub, sin descargar nada.
3. En Power BI, ve a **Obtener datos → Web** y pega el enlace Raw del CSV limpio.

## Contenido

### Módulo 2 · Calidad de datos y EDA

| Archivo | Qué es |
|---|---|
| `Documento_Modulo_2_UNICOLOMBO.docx` · `Diapositivas_Modulo_2_UNICOLOMBO.pdf` | Teoría y diapositivas del módulo |
| `Notebook_1_Teoria_Calidad.ipynb` | Las dimensiones de la calidad de datos, con ejemplos |
| `Notebook_2_Laboratorio_Práctico.ipynb` · `Laboratorio_Modulo_2_Colab.ipynb` | Laboratorio de limpieza y unión de datos en Colab |
| `Clientes_Ventas_Calidad_Datos.csv` · `Clientes_Info.csv` | 60.500 ventas con datos de cliente para el laboratorio de calidad (también en `Diplomado/Modulo_2/`) |
| `ventas_limpias_powerbi.csv` | Resultado limpio, listo para Power BI |

### Módulo 3 · Visualización y storytelling

| Archivo | Qué es |
|---|---|
| `Dataset_Ventas_Retail_M3S2_RAW.csv` · `Dataset_Ventas_Retail_M3S2_REFERENCIA_LIMPIA.csv` | Ventas minoristas en bruto y su versión limpia de referencia, para comparar |
| `Dim_Categorias_M3S2.csv` · `Dim_Zonas_M3S2.csv` | Dimensiones para el modelo en estrella |
| `Diplomado/Modulo_3/` | Datos de redes sociales y de ventas para storytelling |

### Casos adicionales

| Archivo | Qué es |
|---|---|
| `bank_transactions_raw.csv` · `bank_transactions_processed.csv` · `bank_transactions_eda_for_fraud_detection_mejorado.ipynb` | EDA orientado a la detección de fraude en transacciones |
| `europe.csv` | Indicadores demográficos de 36 países europeos (población, esperanza de vida, natalidad) |
| `Dataset.xlsx` · `DataVentas PBI.xlsx` | Libros de Excel para importar en Power BI |
| `PowerBI_Envases_Del_Caribe_Guias/` | Guías de seguimiento de las sesiones 12 y 13: diagnóstico y proyección del OEE, caso *Envases del Caribe* |

## Notas

- Los datos son de práctica, con fines educativos.
- `README.txt` conserva las instrucciones originales del Módulo 2.
- Los archivos `*.txt` dentro de `Diplomado/Modulo_N/` solo sirven para que la carpeta exista.
