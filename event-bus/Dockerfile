# Image
FROM node:alpine

#Set working directory and files
WORKDIR /app
COPY package.json ./
RUN npm i

#Copy rest of the files to avoid cache busting
COPY ./ ./

#Start command
CMD ["npm", "start"]