FROM node:17-alpine3.14
WORKDIR /home/debian/BaseApp/backend/
COPY *.js /home/debian/BaseApp/backend/
COPY package.json /home/debian/BaseApp/backend/.
RUN npm install
CMD ["node","index.js"]
EXPOSE 3000
