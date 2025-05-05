# 🌾 Análisis Estadístico de Rendimiento de Trigo e Infección por Roya

## 📌 Descripción del Proyecto

Este proyecto presenta un análisis estadístico completo a partir de datos recolectados en un experimento con cultivos de trigo. El objetivo es estimar, mediante métodos inferenciales:

- La media del rendimiento por parcela (t/ha)
- La varianza poblacional del rendimiento
- La proporción de infección por roya del tallo en plantas de trigo

El estudio se desarrolló en un entorno controlado de 9 parcelas, con observación de 20 plantas por parcela.

---

## 🛠️ Características Principales

- **Definición formal de variables aleatorias** (discretas y continuas)
- **Identificación de distribuciones teóricas**: normal, binomial y chi-cuadrado
- **Construcción de intervalos de confianza al 95%**:
  - Para la media (distribución t de Student)
  - Para la varianza poblacional (distribución χ²)
  - Para la proporción de infección (distribución normal estándar)
- **Visualizaciones didácticas**:
  - Campana normal con zona sombreada de confianza
  - Distribución χ² con límites destacados
  - Gráfico de barras con error para proporción de infección

---

## 📊 Estructura del Notebook

1. **Definición del problema**
2. **Carga y organización de datos**
3. **Análisis exploratorio**
4. **Intervalo de confianza para la media**
5. **Intervalo de confianza para la varianza**
6. **Intervalo de confianza para la proporción**
7. **Visualización de resultados**
8. **Conclusiones estadísticas**

---

## 🚀 Cómo Usar

1. Cloná este repositorio:

```bash
git clone https://github.com/Fabriciogg8/trigo_inferencia_estadistica.git
```

2. Instalá las dependencias necesarias:

```bash
pip install -r requirements.txt
```

3. Ejecutá el notebook:

```bash
jupyter notebook MetodosCuantitativos.ipynb
```

## 📋 Requisitos
* **Python 3.7+**
* **Librerías principales:**

    * pandas

    * numpy

    * matplotlib

    * seaborn

    * scipy

## 📈 Aplicaciones
Este análisis puede ser útil para:

* Ingenieros agrónomos que deseen evaluar experimentalmente el rendimiento de cultivos

* Investigadores en fitopatología (roya del tallo)

* Estudiantes de métodos cuantitativos o bioestadística

* Científicos de datos aplicados al agro

## 🎯 Resultados Clave
* Estimación puntual del rendimiento medio: 1.93 t/ha

* Intervalo de confianza para la media: [1.69, 2.18] t/ha

* IC 95% para la varianza poblacional: [0.05, 0.37] (t/ha)²

* Proporción estimada de infección: 20% ± 5.8%

* Visualización intuitiva de resultados inferenciales

## 🤝 Contribuciones
¡Las contribuciones son bienvenidas! Podés abrir un issue o enviar un pull request.

## 📧 Contacto
**Fabricio González**
📧 fgonzalezguasque@gmail.com
🔗 LinkedIn