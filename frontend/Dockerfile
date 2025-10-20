# Utilizamos "alpine" porque es la imagen base de linux más ligera.
FROM node:22-alpine
# Directorio de trabajo de la imagen.
WORKDIR /app
# Copia desde el PC (local) al contenedor los JSON.
COPY package*.json ./
# Ejecuta el comando que instala dependencias dentro de la imagen.
RUN npm install
# Copia todo el código fuente del PC (local) al contenedor.
COPY . .
# Expone/abre el puerto 5173 (por defecto de VITE).
EXPOSE 5173
# Ejecuta y arranca NestJs en modo "developer".
CMD ["npm", "run", "dev", "--", "--host"]