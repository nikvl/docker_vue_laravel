FROM node:12-alpine

## Install dependencies
#RUN apt-get update && apt-get install -y \
#    vim \
#    zip \
#    unzip \
#    curl

# Change current user
USER node

CMD ["sh", "-c", "npm install && npm run build && npm run start"]