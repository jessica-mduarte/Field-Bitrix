FROM node:20-slim
WORKDIR /app
COPY package*.json ./
RUN npm install --production
COPY . .
CMD ["sh", "-c", "echo 'Container pronto. Aguardando comando do Cron Job.' && node src/index.js"]
