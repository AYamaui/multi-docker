FROM node:14.14.0-alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY . .
# In package.json we defined another script 'dev' which runs nodemon. It is command line tool to automatically reload the project when any source code is changed
CMD ["npm", "run", "start"]