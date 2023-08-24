# Use a imagem base do Node.js 18 com Alpine
FROM node:18-alpine

# Define o diretório de trabalho dentro do container
WORKDIR /app

# Copia os arquivos do package.json e package-lock.json para o diretório de trabalho
COPY package*.json ./

# Instala as dependências
RUN npm install

# Copia todo o conteúdo da pasta front-end local para o diretório de trabalho no container
COPY . .

# Formata o código (se necessário)
RUN npm run format

# Inicia o servidor de desenvolvimento
CMD ["npm", "run", "dev"]
