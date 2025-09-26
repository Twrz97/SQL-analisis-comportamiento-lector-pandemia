# 📘 Proyecto: Análisis de comportamiento lector durante la pandemia

## 🧩 Contexto  
Durante la pandemia de COVID-19, el hábito de lectura se intensificó. Muchas personas comenzaron a consumir libros desde casa, lo que impulsó el desarrollo de aplicaciones orientadas a lectores.  
Este proyecto conecta a una base de datos de un servicio de lectura y analiza información sobre:  
- Libros  
- Autores  
- Editoriales  
- Calificaciones  
- Reseñas

## 🎯 Objetivos  
- Analizar la estructura de la base de datos.  
- Responder preguntas clave mediante consultas SQL.  
- Documentar hallazgos con claridad y trazabilidad.

## 🛠️ Tecnologías utilizadas  
- **Python 3**  
- **Jupyter Notebook**  
- **SQL**  
- Librerías:  
  - pandas  
  - SQLAlchemy  
  - matplotlib / seaborn

## 📂 Estructura del repositorio  
```  
├── SQL.ipynb          # Notebook principal con análisis
├── images/            # Carpeta con imágenes y visualizaciones generadas
└── README.md          # Documentación del proyecto
```

## ⚙️ Requisitos  
1. Tener instalado **Python 3.9+**  
2. Instalar librerías necesarias:
```
pip install pandas sqlalchemy matplotlib seaborn jupyter
```
3. Acceso a la base de datos (no incluida en este repositorio).

## 🚀 Uso  
1. Clona el repositorio:
```
git clone https://github.com/tuusuario/tu-repo.git
cd tu-repo
```
2. Abre el notebook en Jupyter:
```
jupyter notebook SQL.ipynb
```
3. Ejecuta las celdas para reproducir el análisis.

## 📊 Resultados destacados  
Algunas consultas realizadas:  
- Total de libros publicados después de enero 2000.  
- Identificación de autores más prolíficos.  
- Editoriales con mayor número de publicaciones.  
- Distribución de calificaciones de libros.  
- Reseñas más relevantes por usuarios.

# ⚠️ Nota: Para establecer la conexión es necesario contar con el archivo `CA.pem`, 
el cual no se incluye en este repositorio por motivos de seguridad. 
Debe colocarse en el mismo directorio que el notebook antes de ejecutar el análisis.


## 📌 Notas  
- La base de datos usada para este análisis **no** se incluye en el repositorio por motivos de privacidad.  
- El notebook puede adaptarse fácilmente a otras bases de datos cambiando los parámetros de conexión.

## 📜 Licencia  
Este proyecto está bajo la licencia MIT. Puedes usarlo y modificarlo libremente citando la fuente.
