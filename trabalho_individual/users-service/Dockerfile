FROM node:lts
WORKDIR /user-service
ENV PATH /user-service/node_modules/.bin:$PATH
COPY . .
RUN yarn
# Inicializa a aplicação
CMD yarn db:migrate && yarn watch
EXPOSE 7101