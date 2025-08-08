# 📊 Investigación de Operaciones - Universidad de La Salle

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![GAMSPy](https://img.shields.io/badge/GAMSPy-Latest-green.svg)](https://gamspy.readthedocs.io/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 🎯 Descripción

Este repositorio contiene una colección de **notebooks de Jupyter** con modelos de **Programación Lineal** y **Programación Entera** desarrollados para el curso de **Investigación de Operaciones** del programa de **Ingeniería Industrial** de la **Universidad de La Salle**.

Los notebooks están diseñados como material educativo interactivo, proporcionando implementaciones prácticas de problemas clásicos de optimización utilizando **GAMSPy** y otras herramientas de Python.

## 🏛️ Universidad de La Salle
**Programa:** Ingeniería Industrial  
**Curso:** Investigación de Operaciones  
**Enfoque:** Modelado matemático y optimización aplicada

## 📚 Contenido del Repositorio

### 🔢 Programación Lineal
- **Problemas de Producción**
  - Maximización de utilidades
  - Minimización de costos
  - Asignación de recursos limitados
  
- **Problemas de Transporte y Asignación**
  - Optimización de rutas de distribución
  - Asignación de tareas y recursos
  - Problemas de flujo de red

- **Problemas de Mezclas**
  - Formulación de productos
  - Optimización de dietas
  - Planificación de inversiones

### 🎯 Programación Entera
- **Programación Binaria**
  - Problemas de selección (0-1)
  - Localización de instalaciones
  - Programación de proyectos

- **Programación Entera Mixta**
  - Problemas de lote económico
  - Planificación de producción con setup
  - Optimización de inventarios

## 🛠️ Tecnologías Utilizadas

- **[Python 3.8+](https://www.python.org/)** - Lenguaje de programación principal
- **[GAMSPy](https://gamspy.readthedocs.io/)** - Librería de modelado matemático
- **[Jupyter Notebooks](https://jupyter.org/)** - Entorno interactivo de desarrollo
- **[Pandas](https://pandas.pydata.org/)** - Manipulación y análisis de datos
- **[NumPy](https://numpy.org/)** - Computación numérica
- **[Matplotlib](https://matplotlib.org/)** - Visualización de resultados

## 📁 Estructura del Repositorio

```
📦 investigacion-operaciones-lasalle
├── 📂 programacion-lineal/
│   ├── 📓 01-problema-produccion.ipynb
│   ├── 📓 02-problema-transporte.ipynb
│   ├── 📓 03-problema-dieta.ipynb
│   ├── 📓 04-problema-asignacion.ipynb
│   └── 📓 05-analisis-sensibilidad.ipynb
├── 📂 programacion-entera/
│   ├── 📓 01-problema-mochila.ipynb
│   ├── 📓 02-localizacion-instalaciones.ipynb
│   ├── 📓 03-programacion-proyectos.ipynb
│   └── 📓 04-problemas-mixtos.ipynb
├── 📂 datos/
│   ├── 📄 produccion_datos.csv
│   ├── 📄 transporte_costos.xlsx
│   └── 📄 proyectos_tiempos.json
├── 📂 utils/
│   ├── 🐍 modelos_base.py
│   ├── 🐍 visualizaciones.py
│   └── 🐍 validadores.py
├── 📋 requirements.txt
├── 📖 README.md
└── 📜 LICENSE
```

## 🚀 Instalación y Configuración

### Prerrequisitos
- Python 3.8 o superior
- Jupyter Notebook o JupyterLab
- Git

### Clonar el Repositorio
```bash
git clone https://github.com/tu-usuario/investigacion-operaciones-lasalle.git
cd investigacion-operaciones-lasalle
```

### Crear Entorno Virtual
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### Instalar Dependencias
```bash
pip install -r requirements.txt
```

### Iniciar Jupyter
```bash
jupyter notebook
```

## 📖 Guía de Uso

### Para Estudiantes
1. **Clonar el repositorio** en tu máquina local
2. **Instalar las dependencias** según las instrucciones
3. **Abrir los notebooks** en orden secuencial
4. **Ejecutar cada celda** paso a paso para entender el proceso
5. **Modificar los parámetros** para experimentar con diferentes escenarios

### Para Profesores
1. Los notebooks incluyen **explicaciones teóricas** y **comentarios detallados**
2. Cada problema tiene **múltiples variaciones** para asignaciones
3. Se incluyen **datos de ejemplo** y **casos de estudio reales**
4. **Ejercicios propuestos** al final de cada notebook

## 🎓 Objetivos de Aprendizaje

Al completar este curso, los estudiantes serán capaces de:

- ✅ **Formular problemas** de optimización matemática
- ✅ **Implementar modelos** usando GAMSPy y Python
- ✅ **Interpretar resultados** y análisis de sensibilidad
- ✅ **Aplicar técnicas** de programación lineal y entera
- ✅ **Resolver problemas** industriales reales
- ✅ **Comunicar soluciones** de manera efectiva

## 📋 Lista de Notebooks

| Notebook | Tema | Dificultad | Tipo |
|----------|------|------------|------|
| `01-problema-produccion.ipynb` | Maximización de utilidades | 🟢 Básico | PL |
| `02-problema-transporte.ipynb` | Minimización de costos de envío | 🟡 Intermedio | PL |
| `03-problema-dieta.ipynb` | Optimización nutricional | 🟡 Intermedio | PL |
| `04-problema-asignacion.ipynb` | Asignación óptima de recursos | 🟡 Intermedio | PL |
| `05-analisis-sensibilidad.ipynb` | Análisis post-óptimo | 🔴 Avanzado | PL |
| `01-problema-mochila.ipynb` | Selección de elementos | 🟡 Intermedio | PE |
| `02-localizacion-instalaciones.ipynb` | Problemas de ubicación | 🔴 Avanzado | PE |
| `03-programacion-proyectos.ipynb` | Planificación temporal | 🔴 Avanzado | PE |
| `04-problemas-mixtos.ipynb` | Programación entera mixta | 🔴 Avanzado | PEM |

**Leyenda:** PL = Programación Lineal, PE = Programación Entera, PEM = Programación Entera Mixta

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Si eres estudiante, profesor o profesional y deseas mejorar este material:

1. **Fork** el repositorio
2. **Crea una rama** para tu contribución (`git checkout -b feature/mejora-notebook`)
3. **Realiza tus cambios** y documéntalos apropiadamente
4. **Commit** tus cambios (`git commit -m 'Agrega nuevo ejemplo de programación entera'`)
5. **Push** a la rama (`git push origin feature/mejora-notebook`)
6. **Abre un Pull Request**

### Tipos de Contribuciones
- 📓 Nuevos notebooks con problemas adicionales
- 🐛 Corrección de errores en el código
- 📚 Mejoras en la documentación
- 🎨 Mejoras en visualizaciones
- 📊 Nuevos conjuntos de datos
- 🧪 Casos de estudio adicionales

## 📧 Contacto y Soporte

**Profesor:** [Nombre del Profesor]  
**Email:** profesor@unisalle.edu.co  
**Oficina:** [Ubicación en el campus]  
**Horarios de atención:** [Días y horarios]

Para reportar problemas o hacer preguntas:
- 🐛 **Issues del repositorio:** Para errores técnicos
- 💬 **Discusiones:** Para preguntas conceptuales
- 📧 **Email:** Para consultas privadas

## 📜 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 🙏 Agradecimientos

- **Universidad de La Salle** - Por el apoyo institucional
- **Programa de Ingeniería Industrial** - Por la colaboración académica
- **Comunidad GAMSPy** - Por la excelente herramienta de modelado
- **Estudiantes** - Por su feedback y contribuciones

## 📈 Estadísticas del Repositorio

![Contribuidores](https://img.shields.io/github/contributors/tu-usuario/investigacion-operaciones-lasalle)
![Commits](https://img.shields.io/github/commit-activity/m/tu-usuario/investigacion-operaciones-lasalle)
![Issues](https://img.shields.io/github/issues/tu-usuario/investigacion-operaciones-lasalle)
![Forks](https://img.shields.io/github/forks/tu-usuario/investigacion-operaciones-lasalle)
![Stars](https://img.shields.io/github/stars/tu-usuario/investigacion-operaciones-lasalle)

---

<div align="center">

**🎓 Desarrollado con ❤️ para el aprendizaje de la Investigación de Operaciones**

**Universidad de La Salle - Ingeniería Industrial**

⭐ **¡No olvides dar una estrella si este repositorio te ha sido útil!** ⭐

</div>
