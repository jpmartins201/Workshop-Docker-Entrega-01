FROM node:lts
WORKDIR /chat-service
ENV PATH /chat-service/node_modules/.bin:$PATH
COPY . .
RUN yarn
# Inicializa a aplicação
CMD ["yarn", "watch"]
EXPOSE 7100