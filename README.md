# Aplicación web de control de jornada laboral y nominas (NOMINAI)

Este repositorio ha sido creado con la finalidad de aportar soluciones tecnológicas escalables y profesionales a problemas reales, siendo el escenario escogido uno personal en la empresa donde actualmente presto mis servicios. Toda la información y la documentación principal del proyecto se encuentra disponible públicamente en Google Docs y puede ser apreciada desde el siguiente enlace: 

https://docs.google.com/document/d/1JUa2eU1zfzMu_3-3PrUDwIZ1NgW8ofDO3VXL1E5Wpps/edit?usp=sharing

## Estructura del proyecto 

El proyecto se ha adaptado a las necesidades reales del mercado, donde, en sujeto personal de opinión, he percibido que la mayoría de las ofertas junior tienen como principal interés el uso de React, NestJs, TypeScript, Docker, Vite, Tailwind, Git, Github.

### Lenguajes de Programación

- TypeScript
- JavaScript
- HTML5
- CSS3
- JSON
- SQL

### Frameworks y Librerías

- React
- NestJS
- Tailwind CSS
- Prisma ORM
- JWT (JSON Web Tokens)

### Herramientas de Desarrollo

- Docker
- Vite
- Git
- GitHub
- Visual Studio Code
- Cursor

### Bases de Datos

- PostgreSQL
- SQLite

## Convenciones de Commits

El repositorio utiliza conventional commits para mantener un historial claro y organizado. Consulta el archivo `guia-commits.md` para conocer las convenciones utilizadas.

## Configuración del Entorno

Para trabajar con los proyectos de este repositorio, se recomienda:

1. **Instalar Node.js** (versión 18 o superior)
2. **Instalar Docker y Docker Compose** para la containerización
3. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/nominai.git
   cd nominai
   ```

Yo personalmente utilizo la interfaz gráfica en el día a día pero en este proyecto utilizaré comandos al 100% para mejorar mi experiencia con ellos.

4. **Ejecutar el frontend** (actualmente disponible):
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

5. **Acceder a la aplicación**:
   - Frontend: http://localhost:5173 (Vite dev server)
   - Backend API: Próximamente en http://localhost:3001

## Funcionalidades Principales

- Cálculo automático del precio por hora bruto y neto
- Parser automático de nóminas en PDF
- Visualización gráfica del desglose de conceptos
- Comparativa entre diferentes meses
- Interfaz responsive y moderna
- Autenticación segura con JWT

## Estructura del Proyecto

El proyecto está organizado en dos carpetas principales:

- **frontend/**: Contiene la aplicación React con TypeScript y Vite
  - src/: Código fuente del frontend
  - public/: Archivos estáticos
  - package.json: Dependencias del frontend

- **backend/**: Aquí irá la API con NestJS y Prisma (próximamente)

- **docker-compose.yml**: Para orquestar todos los servicios

## Scripts de Desarrollo

### Frontend (actualmente disponible)
```bash
cd frontend
npm run dev          # Ejecutar en modo desarrollo
npm run build        # Construir para producción
npm run preview      # Vista previa de producción
npm run lint         # Ejecutar linter
```

### Docker (cuando esté configurado)
```bash
docker-compose up -d    # Levantar servicios
docker-compose down     # Parar servicios
docker-compose logs     # Ver logs
```

## Roadmap del Proyecto

### Fase 1: MVP

- [x] Frontend inicializado con Vite + React + TypeScript
- [x] Backend inicializado con NestJs.
- [x] Contenedores docker inicializados y configurados.
- [x] Instalacion de Prisma para el manejo de BD en el backend.
- [ ] Diseño inicial de la base de datos.
- [ ] Backend básico con cálculo de salarios
- [ ] Frontend con formulario y resultados
- [ ] Parser básico de PDF
- [ ] Autenticación JWT

### Fase 2: Mejoras

- [ ] Dashboard avanzado con gráficas
- [ ] Comparativa mensual
- [ ] Exportación a PDF
- [ ] Tests automatizados

### Fase 3: Producción

- [ ] Despliegue en la nube
- [ ] CI/CD con GitHub Actions
- [ ] Documentación completa
- [ ] Demo en vivo

## Contacto

Este portafolio es de carácter público y representa mi deseo por abordar problemas reales y utilizar mis conocimientos para un bien mayor, por favor, no dudes en contactar conmigo si quieres participar, aclarar dudas o participar en otros proyectos.