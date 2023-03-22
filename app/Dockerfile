FROM node:18-alpine
WORKDIR /app
COPY package.json yarn.lock ./
RUN yarn install --production
EXPOSE 3000
COPY . .
CMD ["node", "src/index.js"]



