FROM node:14-alpine AS todofrontend
WORKDIR /app
EXPOSE 3001
ADD node_modules.tar.gz /app
COPY . .
ENTRYPOINT ["npm"]
CMD ["start"]

# Usei como base o código do Felipe Rech no PR dele, pois o meu não estava passando.