# Complete the file :)

# Description : From used to creat a base image
FROM node:latest

# Explain : It is a command to used and execute the new image
#RUN apk add --no-cache python2 g++ make

# Explain : It is the working directory
WORKDIR /app

# Description :copy files and the directories to the container
COPY . .

# Explain : He install dependencies for the project
RUN yarn install --production

# Explain : He execute the file index.js to install the option
CMD ["node", "src/index.js"]
