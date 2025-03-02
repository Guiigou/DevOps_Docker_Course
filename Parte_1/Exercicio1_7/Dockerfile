# Usa a imagem base Uuntu 22.04
FROM ubuntu:22.04

# Define o diretorio de trabalho dentro do container
WORKDIR /usr/src/app

# Instala o curl dentro do container 
RUN apt update && apt install -y curl

# Copia o script do host para dentro do container
COPY script.sh .

# Dá permissão de execussão ao script dentro do container
RUN chmod +x script.sh

# Define o comando padrao quando o container iniciar
CMD ["./script.sh"]
