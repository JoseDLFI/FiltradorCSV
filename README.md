==================================================================================

FILTRADOR CSV v1.0   -   
Centro Meteorológico Provincial Sancti Spíritus, Cuba

==================================================================================



- DESCRIPCIÓN

Aplicación web 100% offline para filtrar múltiples archivos CSV 
por provincia (o columna) y extraer columnas específicas.


- OBJETIVO

Automatizar el procesamiento manual de archivos de datos climáticos del CMPSS.


- CARACTERÍSTICAS PRINCIPALES

   • 100% offline - No requiere conexión a internet

   • Procesamiento por lotes - Múltiples CSV a la vez

   • Filtrado inteligente - Detecta automáticamente "provincia"

   • Selección granular - Elige columnas por archivo

   • Descarga automática - Genera "Filtrado_nombre.csv"



- CÓMO USAR (3 PASOS SENCILLOS)


1. CARGA
   
   • Arrastra o selecciona tus archivos CSV
   
   • Puedes agregar/eliminar archivos individualmente



2. FILTRA
   
   • Selecciona la columna para filtrar (ej: "provincia")

   • Elige el valor específico (ej: "Sancti Spíritus")



3. EXTRAE Y DESCARGA

   • Para cada CSV, selecciona las columnas a extraer

   • Las columnas de uso frecuente (D, M, MS, SPI*) se seleccionan automáticamente
   • Click en "Filtrar y Descargar"


- FORMATOS SOPORTADOS

• CSV con delimitador: coma (,), punto y coma (;) o tabulación

• Encoding: UTF-8 recomendado

• Tamaño: Optimizado para máquinas con 2GB RAM


- COLUMNAS RECOMENDADAS (Detección automática)

• D, M, MS → Para archivos areas_*.csv

• SPI1, SPI3, SPIN... → Para archivos Indice*.csv

• municipio → Para filtros municipales


- TECNOLOGÍA

• HTML5 + CSS3 + JavaScript vanilla

• File API, Blob API, Web Workers (ligero)

• Sin librerías externas - 100% independiente



- NOTAS IMPORTANTES

• Verificar que los CSV tengan encabezados en primera fila !!!
• La aplicación funciona COMPLETAMENTE en tu navegador (no importa el sistema operativo)
• Los datos NUNCA se envían a internet


• Si cierras la pestaña, se pierde el progreso


- REINICIAR PROCESO

• Usa el botón "Procesar más archivos" después de descargar

• O recarga la página para empezar desde cero



- SOPORTE Y MEJORAS

• Desarrollado para uso interno del CMPSS

• Reportar problemas o sugerencias al especialista de clima del CMPSS

• Versión actual: 1.0 (2026)


- CONSEJOS PRÁCTICOS

• Para archivos muy grandes (>50MB), procesar en lotes pequeños

• "Sancti Spíritus" se auto-selecciona si existe en los datos


- CRÉDITOS

Desarrollado para optimizar el flujo de trabajo meteorológico 
del departmento de Meteorología Aplicada del Centro Meteorológico Provincial Sancti Spíritus, Cuba.

