FROM node:12.18.1
COPY . /app

ENV BACKEND_URL=http://odds-micro:8080/api/
RUN yarn install && cd /app/
CMD ["yarn", "--cwd","/app","start"]