# 🎨 El jardín de las delicias — Puzzle Checker

Una aplicación web interactiva que utiliza IA (Google Gemini) para verificar si se ha completado correctamente un puzzle de "El jardín de las delicias" de Hieronymus Bosch.

## 🎯 ¿Qué hace?

Esta aplicación verifica:
- ✅ Puzzle completado del "Jardín de las delicias"
- ✅ Persona tumbada en la imagen
- ✅ Camiseta rojiblanca del Atlético de Madrid visible
- ✅ Código de sesión en papel junto al puzzle

## 🌐 Aplicación en vivo

**[🚀 Usar aplicación funcional](https://elloza.github.io/puzzle-checker-public/)**

> ✅ **Aplicación completa**: Conectada con IA real (Google Gemini) para verificación de puzzles.

## 🚀 Características

- **Interfaz elegante** con tema oscuro inspirado en la obra de Bosch
- **Análisis de IA** usando Google Gemini Vision
- **Verificación en tiempo real** de múltiples elementos
- **Mensajes secretos** desbloqueables
- **Códigos de sesión** únicos
- **Diseño responsive** para móviles y desktop

## 🛠️ Tecnologías

### Frontend
- **HTML5** + **CSS3** (Variables CSS, Grid, Flexbox)
- **JavaScript ES6+** (Fetch API, FormData)
- **Google Fonts** (Playfair Display, Inter)
- **Responsive Design**

### Backend (no incluido en esta demo)
- **FastAPI** (Python)
- **Google Gemini AI** API
- **Pydantic** para validación
- **python-dotenv** para configuración

## 📁 Estructura del proyecto

```
puzzle-checker/
├── frontend/
│   ├── index.html          # Aplicación principal
│   └── README.md          # Este archivo
├── api/
│   ├── main.py            # Servidor FastAPI
│   ├── requirements.txt   # Dependencias Python
│   └── .env              # Variables de entorno
└── docker-compose.yml     # Contenedores Docker
```

## 🎮 Cómo usar

1. **Genera un código** presionando "actualizar"
2. **Escribe el código** en un papel
3. **Completa el puzzle** de "El jardín de las delicias"
4. **Colócate** con tu camiseta del Atleti junto al puzzle
5. **Haz una foto** que incluya todo
6. **Sube la imagen** y presiona "Comprobar"
7. **¡Descubre el mensaje secreto!** si todo está correcto

## 🔧 Instalación local

```bash
# Clonar repositorio
git clone https://github.com/elloza/puzzle-checker-public.git
cd puzzle-checker-public

# Abrir frontend
open index.html
# O usar un servidor local
python -m http.server 8000
```

### Para el backend completo:

```bash
# Instalar dependencias
pip install -r api/requirements.txt

# Configurar variables de entorno
echo "GEMINI_API_KEY=tu_clave_aqui" > api/.env

# Ejecutar servidor
uvicorn api.main:app --reload --port 8080
```

## 🎨 Capturas

| Interfaz principal | Verificación exitosa | Mensaje secreto |
|-------------------|---------------------|-----------------|
| ![Interface](https://via.placeholder.com/300x200?text=Demo+1) | ![Success](https://via.placeholder.com/300x200?text=Demo+2) | ![Secret](https://via.placeholder.com/300x200?text=Demo+3) |

## 🤝 Contribuir

¡Las contribuciones son bienvenidas!

1. Fork el proyecto
2. Crea una rama (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver `LICENSE` para más detalles.

## 👨‍💻 Autor

**elloza** - [GitHub](https://github.com/elloza)

## 🙏 Agradecimientos

- **Hieronymus Bosch** por "El jardín de las delicias"
- **Google Gemini** por la tecnología de IA
- **Atlético de Madrid** por la inspiración rojiblanca
- **GitHub Pages** por el hosting gratuito

---

⭐ ¡Dale una estrella si te gusta el proyecto!