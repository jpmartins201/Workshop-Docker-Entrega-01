FROM node:lts
WORKDIR /chat-app
ENV PATH /chat-app/node_modules/.bin:$PATH
COPY . .
RUN yarn
# Inicializa a aplicação
CMD ["yarn", "watch"]
EXPOSE 7001