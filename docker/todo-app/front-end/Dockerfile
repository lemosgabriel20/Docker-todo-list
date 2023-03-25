FROM node:14-alpine AS todofrontend
WORKDIR /usr/app
EXPOSE 3000
ADD node_modules.tar.gz ./todo-app/front-end
COPY . .
RUN npm install
CMD ["npm", "start"]