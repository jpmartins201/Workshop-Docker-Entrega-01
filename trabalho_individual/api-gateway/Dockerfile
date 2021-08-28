FROM node:lts
WORKDIR /api-gateway
ENV PATH /api-gateway/node_modules/.bin:$PATH
COPY . .
RUN yarn
# Inicializa a aplicação
CMD ["yarn", "watch"]
EXPOSE 7000