# 📊 Análisis de Datos de Recursos Humanos (HR)

Un proyecto de análisis y visualización de datos sobre recursos humanos, realizado por el equipo 3 del Módulo 3.

---

## 📁 Estructura del Proyecto

```
project-da-promo-63-modulo-3-team-3/
│
├── README.md                        # Este archivo (información general)
├── hr.csv                           # Datos originales sin limpiar
├── df_hr_limpio.csv                 # Datos limpios listos para analizar
│
├── fases/                           # Carpeta con las 4 fases del proyecto
│   ├── fase_1_2_eda_limpieza.ipynb         # Exploración y limpieza de datos
│   ├── fase_3_visualizacion.ipynb          # Gráficos y visualizaciones
│   └── fase_4_diseño_BBDD.ipynb            # Diseño de base de datos
│
└── consultas/                       # Carpeta con análisis y visualizaciones adicionales
    ├── posibles_consultas.ipynb             # Preguntas y análisis de datos
    ├── Saray_consulta_fase_3_visualizacion.ipynb    # Análisis de Saray
    ├── visualizaciones-carol.ipynb          # Visualizaciones de Carol
    ├── visualizaciones-eleonora.ipynb       # Visualizaciones de Eleonora
    └── visualizaciones-maria.ipynb          # Visualizaciones de María
```

---

## 📋 Documentos Principales

### **Datos**
- **`hr.csv`**: Dataset original con todos los datos de recursos humanos sin procesar
- **`df_hr_limpio.csv`**: Dataset ya limpio y preparado (sin errores, sin datos faltantes)

### **Fases del Proyecto**

#### 📍 **Fase 1 & 2: Exploración y Limpieza** 
- **Archivo**: `fases/fase_1_2_eda_limpieza.ipynb`
- **Qué hace**: Examina los datos, identifica problemas y los limpia
- **Para aprender**: Cómo trabajar con datos desordenados

#### 📊 **Fase 3: Visualización**
- **Archivo**: `fases/fase_3_visualizacion.ipynb`
- **Qué hace**: Crea gráficos para entender los datos visualmente
- **Para aprender**: Cómo hacer gráficos bonitos e informativos

#### 🗄️ **Fase 4: Base de Datos**
- **Archivo**: `fases/fase_4_diseño_BBDD.ipynb`
- **Qué hace**: Diseña cómo almacenar los datos en una base de datos
- **Para aprender**: Estructura y organización de datos

### **Consultas y Análisis**
- **`posibles_consultas.ipynb`**: Preguntas interesantes que se pueden responder con los datos
- **`visualizaciones-carol.ipynb`**: Análisis y gráficos creados por Carol
- **`visualizaciones-eleonora.ipynb`**: Análisis y gráficos creados por Eleonora
- **`visualizaciones-maria.ipynb`**: Análisis y gráficos creados por María
- **`Saray_consulta_fase_3_visualizacion.ipynb`**: Análisis y visualizaciones de Saray

---

## 🚀 Cómo Usar Este Proyecto

### **1. Empezar por aquí** 
Si es tu primera vez, abre en este orden:
1. `fases/fase_1_2_eda_limpieza.ipynb` → Entiende cómo se limpian los datos
2. `fases/fase_3_visualizacion.ipynb` → Ve cómo se crean gráficos
3. Los archivos en `consultas/` → Mira ejemplos de análisis diferentes

### **2. Para ejecutar el código**

**Requisitos**:
- Python 3.7+
- Jupyter Notebook o JupyterLab
- Librerías necesarias: `pandas`, `numpy`, `matplotlib`, `seaborn`

**Instalación de librerías** (abre una terminal):
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**Ejecutar los Notebooks**:
1. Descarga o clona este repositorio
2. Abre una terminal en la carpeta del proyecto
3. Escribe: `jupyter notebook`
4. Se abrirá una ventana en tu navegador
5. Haz clic en cualquier archivo `.ipynb` para abrirlo

### **3. Entender el flujo de datos**

```
hr.csv (datos originales)
    ↓
fase_1_2_eda_limpieza.ipynb (se limpian)
    ↓
df_hr_limpio.csv (datos limpios)
    ↓
fase_3_visualizacion.ipynb (se visualizan)
    ↓
Gráficos y insights (conclusiones)
```

---

## 📚 ¿Qué es cada cosa?

- **EDA** (Exploratory Data Analysis): Exploración de datos para entenderlos
- **Limpieza**: Quitar datos incorrectos, incompletos o duplicados
- **Visualización**: Crear gráficos para ver patrones fácilmente
- **Base de Datos**: Sistema para almacenar y organizar información

---

## 💡 Tips para Principiantes

✅ Lee los comentarios dentro del código  
✅ Ejecuta el código celda por celda (no todo de una vez)  
✅ Observa qué hace cada comando  
✅ Cambia valores y experimenta  
✅ Si hay un error, lee el mensaje (¡a veces es muy útil!)

---

## 👥 Integrantes del Equipo

- Carol (carolsan-5)
- Eleonora
- María
- Saray

---

**¡Happy Data Analysis! 📈**