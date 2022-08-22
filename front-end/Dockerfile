FROM node:16

WORKDIR /home/nicole/Documentos/Programação/Driven/Projetos/infraestrutura/projeto23-drivenops/front-end/app

COPY . .

EXPOSE 5000

RUN npm i
RUN npm run build

RUN mkdir -p /var/www/html
RUN mv build/* /var/www/html

WORKDIR /

RUN rm -rf /app