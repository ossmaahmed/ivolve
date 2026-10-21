FROM node:22-alpine
WORKDIR /app
RUN apk update && apk upgrade --no-cache
COPY package.json package-lock.json ./
RUN npm ci --omit=dev
COPY app.js ./
EXPOSE 3000
CMD ["node", "app.js"]
