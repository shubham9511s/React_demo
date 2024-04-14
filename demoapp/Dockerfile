FROM node:20 

#this is working directory 

WORKDIR /app 

# COPY all the file inside the working directory 

COPY . .

#RUN command
RUN npm install

# Port 
EXPOSE  5173

CMD [ "npm","run","dev" ]  



