FROM node:16

WORKDIR /home/nicole/Documentos/Programação/Driven/Projetos/infraestrutura/projeto23-drivenops/back-end/src

COPY . .

EXPOSE 5000

RUN npm i
RUN npm run build

CMD ["npm", "start"]