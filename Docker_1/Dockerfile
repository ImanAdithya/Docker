#Base Image
FROM node:20-alpine

#Working Directory
WORKDIR /app

#Copy Package  Json file
COPY Package.json .

#Install Dependencies
RUN npm install

#Copy the files
COPY . .

#Run the App
CMD ["node","index.js"]