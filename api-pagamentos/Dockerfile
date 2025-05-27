# Usa imagem oficial do PHP com servidor embutido
FROM php:8.2-cli

# Define o diretório de trabalho
WORKDIR /app

# Copia os arquivos da API
COPY . .

# Expor a porta que vamos usar no servidor
EXPOSE 3003

# Rodar o servidor embutido na porta 8000
CMD ["php", "-S", "0.0.0.0:3003"]
