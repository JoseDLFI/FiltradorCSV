# 🔍 Filtrador CSV v1.0

<div align="center">
  <h3>Centro Meteorológico Provincial Sancti Spíritus, Cuba</h3>
  <p><i>Aplicación web 100% offline para filtrar múltiples archivos CSV</i></p>
</div>

---

## 📋 Descripción

Aplicación web **100% offline** para filtrar múltiples archivos CSV por provincia (o columna) y extraer columnas específicas. Diseñado como un único archivo HTML para máxima portabilidad.

---

## 🎯 Objetivo

Automatizar el procesamiento manual de archivos de datos climáticos del CMPSS, eliminando tareas repetitivas y minimizando errores humanos.

---

## ✨ Características Principales

| Característica | Descripción |
|----------------|-------------|
| 🔒 **100% offline** | No requiere conexión a internet |
| 📦 **Procesamiento por lotes** | Múltiples archivos CSV a la vez |
| 🧠 **Filtrado inteligente** | Detecta automáticamente la columna "provincia" |
| 🎚️ **Selección granular** | Elige columnas específicas por archivo |
| ⬇️ **Descarga automática** | Genera archivos con prefijo `Filtrado_nombre.csv` |

---

## 🚀 Cómo Usar (3 Pasos Sencillos)

### 1️⃣ **CARGA**
- Arrastra o selecciona tus archivos CSV
- Puedes agregar o eliminar archivos individualmente según necesites

### 2️⃣ **FILTRA**
- Selecciona la columna para filtrar (ej: `"provincia"`)
- Elige el valor específico (ej: `"Sancti Spíritus"`)

### 3️⃣ **EXTRAE Y DESCARGA**
- Para cada archivo CSV, selecciona las columnas a extraer
- Las columnas de uso frecuente (`D`, `M`, `MS`, `SPI*`) se seleccionan automáticamente
- Haz clic en **"Filtrar y Descargar"**

---

## 📁 Formatos Soportados

| Formato | Detalles |
|---------|----------|
| **Delimitadores** | Coma (,), punto y coma (;) o tabulación |
| **Encoding** | UTF-8 (recomendado) |
| **Tamaño** | Optimizado para máquinas con 2GB RAM |

---

## 🧩 Columnas Recomendadas (Detección Automática)

| Tipo de Archivo | Columnas Detectadas |
|-----------------|---------------------|
| `areas_*.csv` | `D`, `M`, `MS` |
| `Indice*.csv` | `SPI1`, `SPI3`, `SPIN`... |
| Filtros municipales | `municipio` |

---

## 🛠️ Tecnología

| Componente | Tecnología |
|------------|------------|
| **Lenguajes** | HTML5 + CSS3 + JavaScript vanilla |
| **APIs** | File API, Blob API |
| **Dependencias** | **Sin librerías externas** - 100% independiente |

---

## ⚠️ Notas Importantes

- ✅ Verificar que los CSV tengan **encabezados en la primera fila**
- ✅ La aplicación funciona **completamente en tu navegador** (independiente del sistema operativo)
- ✅ Los datos **NUNCA se envían a internet**
- ⚠️ Si cierras la pestaña, **se pierde el progreso** (no hay almacenamiento persistente)

---

## 🔄 Reiniciar Proceso

- Usa el botón **"Procesar más archivos"** después de descargar
- O **recarga la página** para empezar desde cero

---

## 💡 Consejos Prácticos

- Para archivos muy grandes (>50MB), procesar en **lotes pequeños**
- El valor `"Sancti Spíritus"` se **auto-selecciona** si existe en los datos
- Útil para **filtrar ficheros CSV de cualquier origen**, siempre que contenga la primera fila con encabezados de columna

---

## 🤝 Soporte y Mejoras

- **Desarrollado para uso interno del CMPSS**
- Reportar problemas o sugerencias al **especialista de clima del CMPSS**
- **Versión actual:** 1.0 (2026)

---

## 👨‍💻 Créditos

Desarrollado para optimizar el flujo de trabajo meteorológico del departamento de **Meteorología Aplicada** del Centro Meteorológico Provincial Sancti Spíritus, Cuba.

---

<div align="center">
  <p>
    <a href="https://josedlfi.github.io/FiltradorCSV/Filtrador_CSV_v1.0.html">🔗 Ver aplicación en vivo</a>
  </p>
  <p>
    <small>📅 Última actualización: Abril 2026</small>
  </p>
</div>
