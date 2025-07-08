# Reejecutar después del reinicio para generar el archivo README.md estético para GitHub

readme_content = f"""\
<h1 align="center">Hola 👋, soy Juan Pablo Correa Gómez</h1>
<h3 align="center">Tecnólogo en Análisis y Desarrollo de Software</h3>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</p>

---

### ✨ Sobre mí

👨‍💻 Soy apasionado por crear soluciones digitales que mejoren procesos reales en entornos productivos.  
💡 Siempre estoy aprendiendo nuevas tecnologías para fortalecer mi perfil como desarrollador.  
🎯 Me destaco por el pensamiento lógico, la responsabilidad y el trabajo en equipo.

---

### 🧠 Tecnologías que manejo
- **Lenguajes:** PHP, JavaScript, HTML, CSS
- **Base de datos:** MySQL
- **Herramientas:** Git, GitHub, VS Code
- **Metodologías:** SCRUM (básico)

---

### 🚀 Proyectos destacados
- 🧮 **Software para cálculo de incentivos**  
  Sistema para calcular incentivos de operarias según su eficiencia.

- 🛠 **Control de tiempos muertos de mecánicos**  
  Herramienta para monitorear y reducir periodos de inactividad.

- 🌐 **Plataforma de emprendimientos (SENA)**  
  Proyecto web para publicar, ver y gestionar emprendimientos.

---

### 📫 Contáctame
📧 jcorreagomez761@gmail.com

---

### 📊 Estadísticas de GitHub
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chuoDBJLihod&show_icons=true&theme=blueberry" alt="chuoDBJLihod stats"/>
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chuoDBJLihod&theme=blueberry"/>
</p>

---

### ⚡ Frase que me inspira
> *"El software es una gran combinación entre arte e ingeniería." – Bill Gates*
"""

# Guardar archivo README.md
readme_path = "/mnt/data/README_chuoDBJLihod.md"
with open(readme_path, "w", encoding="utf-8") as f:
    f.write(readme_content)

readme_path
