# 📅 Generador de Horarios Académicos

Aplicación web para generar horarios de clases de forma visual e interactiva.

## ✨ Funcionalidades

- Registro del solicitante del horario
- Definición de múltiples grupos
- Catálogo de materias con horas semanales configurables
- Asignación de materias por grupo (pueden variar entre grupos)
- Configuración de días hábiles, horario de entrada/salida y recesos
- Balance visual de horas disponibles vs. asignadas por docente
- Generación automática del horario con distribución equitativa
- Vista de tabla con código de colores por materia
- Resumen de docentes y leyenda de materias

## 🚀 Cómo usar

### Instalación local

```bash
npm install
npm run dev
```

Abre [http://localhost:5173](http://localhost:5173) en tu navegador.

### Build para producción

```bash
npm run build
```

## 🌐 Despliegue en Vercel

1. Sube este proyecto a un repositorio de GitHub
2. Ve a [vercel.com](https://vercel.com) y conecta tu cuenta de GitHub
3. Importa el repositorio → Vercel detecta Vite automáticamente
4. Haz clic en **Deploy** → tu app estará disponible en minutos

## 🛠️ Tecnologías

- React 18
- Vite 4
- CSS-in-JS (estilos en línea)
