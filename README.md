# MindLearn — Plataforma LMS de Psicología

Plataforma de aprendizaje online (LMS) enfocada en psicología de la mente humana. Construida como SPA en HTML/CSS/JS puro, sin dependencias de servidor.

## Características

- 🔐 Sistema de autenticación con 3 roles: Administrador, Profesor, Alumno
- 📚 2 cursos completos con módulos, lecciones y contenido multimedia
- 📝 Evaluaciones con preguntas tipo test y verdadero/falso
- 📊 Sistema de progreso y calificaciones por alumno
- 👥 Gestión completa de usuarios, roles y matriculaciones
- 🌙 Modo oscuro / claro
- 🔌 Demostración de API REST (funcionalidad avanzada)

## Estructura del proyecto

```
mindlearn/
├── index.html       # Aplicación completa (SPA autocontenida)
├── vercel.json      # Configuración de despliegue en Vercel
├── .gitignore
└── README.md
```

## Despliegue en Vercel

### Opción A — Desde la web de Vercel (más fácil)

1. Sube este proyecto a GitHub (ver instrucciones abajo)
2. Entra en [vercel.com](https://vercel.com) e inicia sesión
3. Clic en **"Add New Project"**
4. Importa el repositorio de GitHub
5. Vercel lo detecta como proyecto estático automáticamente
6. Clic en **"Deploy"** → listo en segundos

### Opción B — Desde la CLI de Vercel

```bash
# Instalar Vercel CLI
npm install -g vercel

# Dentro de la carpeta del proyecto
vercel

# Para producción
vercel --prod
```

## Accesos de demostración

| Rol           | Email                    | Contraseña  |
|---------------|--------------------------|-------------|
| Administrador | admin@mindlearn.es       | admin123    |
| Profesor      | prof@mindlearn.es        | prof123     |
| Alumno        | ana@mindlearn.es         | alumno123   |

## Tecnologías

- HTML5 / CSS3 / JavaScript ES5+ (sin frameworks, sin dependencias)
- Google Fonts: Syne + DM Sans
- 100% autocontenido — el logo va embebido en base64
