# ☄️ Dashboard de Asteroides NASA

**Visualización interactiva de datos reales sobre asteroides cercanos a la Tierra.**  
Este proyecto utiliza la **API pública de la NASA (Near Earth Object Web Service - NEO)** para obtener información en tiempo real sobre asteroides que pasan cerca de nuestro planeta y los presenta de forma visual, accesible y educativa mediante **Streamlit** y **Plotly**.

---

## 🌌 Motivación

Todo comenzó con una pregunta curiosa y aterradora a la vez:  
> *¿Qué pasaría si un meteorito cayera en la Tierra? ¿Sería peligroso? ¿Qué tan seguido ocurre algo así?*

A partir de esta duda nació este dashboard, que transforma datos astronómicos en gráficos comprensibles.  
El objetivo es **acercar la ciencia espacial al público general**, mostrando cómo la tecnología puede ayudarnos a entender mejor el universo que nos rodea.

---

## 🧠 Descripción del Proyecto

El **Dashboard de Asteroides NASA** permite:
- Consultar asteroides cercanos a la Tierra en un rango de fechas.
- Analizar sus características: tamaño, velocidad, distancia y peligrosidad.
- Aplicar filtros personalizados.
- Visualizar los datos mediante gráficos interactivos y un mapa 3D.

Toda la información proviene de la [NASA Open APIs](https://api.nasa.gov/).

---

## ⚙️ Tecnologías Utilizadas

- [Python 3.9+](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Plotly Express](https://plotly.com/python/plotly-express/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Requests](https://requests.readthedocs.io/en/latest/)

---

## 🧩 Instalación y Ejecución

1. **Cloná este repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/Dashboard-Asteroides.git
   cd Dashboard-Asteroides
   ```

2. **Instalá las dependencias:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Ejecutá la aplicación con Streamlit:**
   ```bash
   streamlit run DashboardAst.py
   ```

4. **Abrí el enlace local que te aparece** (por ejemplo `http://localhost:8501`).

---

## 🔑 Uso

1. Ingresá tu **API Key de la NASA** en el panel lateral (podés usar la de prueba incluida).
2. Elegí un rango de fechas.
3. Presioná **“Obtener datos”**.
4. Explorá las pestañas disponibles:

### 📊 Análisis de Datos
- Línea de tiempo de asteroides detectados por día.  
- Gráfico de dispersión (velocidad vs distancia).  
- Histograma del tamaño máximo.  
- Gráfico circular con la proporción de asteroides peligrosos.

### 🌍 Mapa 3D
Simula la ubicación de los asteroides cercanos a la Tierra con coordenadas generadas aleatoriamente, mostrando su tamaño y nivel de peligrosidad.

### ℹ️ Acerca de
Explica la idea del proyecto, su propósito educativo y los detalles técnicos de su desarrollo.

---

## 📁 Estructura del Proyecto

```
📦 Dashboard-Asteroides
 ┣ 📜 DashboardAst.py        # Script principal de Streamlit
 ┣ 📜 requirements.txt       # Librerías necesarias
 ┗ 📜 README.md              # Documentación del proyecto
```

---

## 🪐 Ejemplo Visual

![Ejemplo de Dashboard](https://raw.githubusercontent.com/tu-usuario/Dashboard-Asteroides/main/demo/dashboard_preview.png)

*(Podés agregar una captura de pantalla del dashboard en ejecución)*

---

## 🧑‍💻 Autor

**Nahuel Nicolás Martín**  
📧 Contacto: [tu-email@example.com]  
📍 Argentina  
🎓 Estudiante de Ciencia de Datos - Instituto Tecnológico Beltrán

---

## 🌠 Licencia

Este proyecto se distribuye bajo la licencia **MIT**.  
Podés usarlo, modificarlo y compartirlo libremente, citando la fuente.

---

> “El miedo a lo desconocido puede transformarse en curiosidad,  
> y la curiosidad en conocimiento.”  
> — *Dashboard de Asteroides NASA*
