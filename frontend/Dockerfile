FROM node:24
WORKDIR /app
COPY . .
RUN npm install -g npm@11.14.0
COPY .env.sample .env
EXPOSE 5173
CMD ["npm","run","dev","--","--host"]
