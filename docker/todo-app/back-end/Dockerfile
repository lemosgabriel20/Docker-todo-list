FROM node:14-alpine AS todobackend
WORKDIR /usr/app
EXPOSE 3001
ADD node_modules.tar.gz ./todo-app/back-end
COPY . .
RUN npm install
CMD ["npm", "start"]