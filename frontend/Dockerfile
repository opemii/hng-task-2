FROM node:current-alpine
WORKDIR /app
COPY package.json package.json
RUN yarn install

COPY . .
EXPOSE 3000:3000
CMD ["yarn","start"]