FROM node:alpine
WORKDIR /app
COPY package.json package-lock.json ./
RUN npm install

COPY src ./src
COPY public ./public
COPY next.config.js .
COPY tsconfig.json .
CMD npm run dev