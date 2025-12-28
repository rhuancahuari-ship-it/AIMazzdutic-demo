# 🎓 AIMazzdutic

> **Tu espacio de trabajo inteligente para crear material educativo de alta calidad**

[![Estado](https://img.shields.io/badge/estado-en%20desarrollo-yellow)]() [![Privado](https://img.shields.io/badge/visibilidad-privado-red)]() [![Licencia](https://img.shields.io/badge/licencia-privada-blue)]()

## 📖 Descripción

**AIMazzdutic** es una plataforma educativa innovadora que integra múltiples inteligencias artificiales en un único espacio de trabajo, diseñado específicamente para docentes que necesitan generar, organizar y personalizar material didáctico de manera eficiente.

Plataforma educativa con IA integrada para generación de material didáctico, editor Markdown, múltiples IAs, personalización visual y exportación DOCX/PDF.

## ✨ Características Principales

### 🤖 Múltiples IAs Integradas
- **GPT-4** (OpenAI) - Generación de texto avanzada
- **Claude 3** (Anthropic) - Análisis y razonamiento
- **Gemini** (Google AI) - Multimodalidad
- **Grok** (xAI) - Información actualizada
- **DALL·E 3** - Generación de imágenes
- **ElevenLabs** - Síntesis de voz/podcasts

### 📝 Editor Markdown Avanzado
- Vista previa en tiempo real
- Soporte completo Markdown/LaTeX
- Sintaxis resaltada
- Botones de inserción rápida
- Autoguardado

### 🎨 Personalización Visual
- Colores personalizados para encabezados (H1-H6)
- Estilos de tablas configurables
- Formato de listas y viñetas
- Fuentes y tamaños ajustables
- Temas claro/oscuro

### 📤 Exportación Profesional
- **DOCX** con estilos aplicados
- **PDF** de alta calidad
- **Markdown** limpio
- **HTML** con CSS

### 🤝 Colaboración y Automatización
- Espacios de trabajo organizados
- Tareas programadas
- Bandeja de entrada
- Sistema de recordatorios
- Historial de versiones

## 🏗️ Arquitectura del Proyecto

```
AIMazzdutic/
├── frontend/              # Interfaz de usuario (React/Next.js)
│   ├── components/       # Componentes reutilizables
│   ├── pages/           # Páginas de la aplicación
│   ├── styles/          # Estilos CSS/TailwindCSS
│   └── utils/           # Utilidades frontend
├── backend/              # Servidor y APIs (Node.js/FastAPI)
│   ├── api/             # Endpoints API
│   ├── models/          # Modelos de datos
│   ├── services/        # Lógica de negocio
│   └── integrations/    # Conexiones con IAs
├── database/             # Esquemas y migraciones
├── docs/                 # Documentación del proyecto
└── tests/                # Pruebas automatizadas
```

## 🚀 Roadmap de Desarrollo

### Fase 1: MVP (4 semanas) ✅ En progreso
- [x] Configuración inicial del repositorio
- [ ] Editor Markdown básico
- [ ] Integración con GPT-4
- [ ] Selector de tipo de material
- [ ] Exportación a Markdown

### Fase 2: Integraciones IA (3 semanas)
- [ ] Selector múltiple de IAs
- [ ] Prompts predefinidos por tipo
- [ ] Generación de imágenes (DALL·E)
- [ ] Sistema de créditos/tokens

### Fase 3: Personalización (2 semanas)
- [ ] Sistema de colores
- [ ] Exportación DOCX/PDF
- [ ] Panel lateral completo
- [ ] Temas visuales

### Fase 4: Automatización (3 semanas)
- [ ] Tareas programadas
- [ ] Notificaciones
- [ ] Colaboración multiusuario
- [ ] Sistema de plantillas

## 💻 Stack Tecnológico

### Frontend
- **Framework:** Next.js 14 (React)
- **Estilos:** TailwindCSS
- **Editor:** Monaco Editor / CodeMirror
- **Markdown:** React Markdown + Remark
- **Estado:** Zustand / Context API

### Backend
- **Servidor:** Next.js API Routes / FastAPI
- **Base de datos:** Supabase / Firebase
- **Autenticación:** NextAuth.js / Supabase Auth
- **Storage:** Supabase Storage / AWS S3

### Integraciones IA
- OpenAI SDK (GPT-4, DALL·E)
- Anthropic SDK (Claude)
- Google AI SDK (Gemini)
- xAI API (Grok)
- ElevenLabs API (Audio)

### DevOps
- **Hosting:** Vercel / Netlify
- **CI/CD:** GitHub Actions
- **Monitoreo:** Sentry
- **Analytics:** Vercel Analytics

## 📦 Instalación (Próximamente)

```bash
# Clonar el repositorio
git clone https://github.com/rhuancahuari-ship-it/AIMazzdutic.git

# Instalar dependencias
cd AIMazzdutic
npm install

# Configurar variables de entorno
cp .env.example .env.local

# Iniciar servidor de desarrollo
npm run dev
```

## 🔐 Variables de Entorno

```env
# OpenAI
OPENAI_API_KEY=tu_clave_aqui

# Anthropic
ANTHROPIC_API_KEY=tu_clave_aqui

# Google AI
GOOGLE_AI_API_KEY=tu_clave_aqui

# Base de datos
DATABASE_URL=tu_url_aqui
NEXT_PUBLIC_SUPABASE_URL=tu_url_aqui
NEXT_PUBLIC_SUPABASE_ANON_KEY=tu_clave_aqui
```

## 🎯 Casos de Uso

### Para Docentes de Historia
- Generar situaciones significativas contextualizadas
- Crear fichas de práctica con lecturas académicas
- Diseñar evaluaciones con preguntas de múltiple opción
- Elaborar material con metodologías activas (ABP, ABPj, ABI)

### Para Docentes de Matemáticas
- Generar ejercicios con LaTeX
- Crear guías paso a paso
- Diseñar problemas contextualizados
- Exportar con fórmulas renderizadas

### Para Cualquier Área
- Material personalizado por competencia
- Aplicación de principios de neuroeducación
- Diseño Universal para el Aprendizaje (DUA)
- Exportación lista para imprimir o compartir

## 📊 Estado del Proyecto

| Componente | Estado | Progreso |
|------------|--------|----------|
| Repositorio | ✅ Creado | 100% |
| Documentación | ✅ Completa | 100% |
| Frontend | 🚧 En desarrollo | 0% |
| Backend | 🚧 Pendiente | 0% |
| Integraciones IA | 🚧 Pendiente | 0% |
| Testing | 🚧 Pendiente | 0% |

## 👨‍💻 Autor

**Docente Peruano Innovador**
- Especialista en educación y tecnología
- Experto en automatización educativa
- Implementador de flujos con n8n y Make.com
- Defensor de la neuroeducación y el DUA

## 📄 Licencia

Este es un proyecto **privado** y personal. Todos los derechos reservados.

## 🔗 Enlaces Útiles

- [Documentación completa](./docs/)
- [Guía de contribución](./CONTRIBUTING.md)
- [Changelog](./CHANGELOG.md)
- [Roadmap detallado](./docs/roadmap.md)

---

⭐ **Proyecto en desarrollo activo** | Última actualización: Diciembre 2025
