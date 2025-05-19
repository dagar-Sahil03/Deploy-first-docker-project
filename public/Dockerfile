FROM node

WORKDIR /app

COPY . ./

RUN npm install

# Expose the port the app runs on
EXPOSE 80

CMD ["node", "server.js"]      
