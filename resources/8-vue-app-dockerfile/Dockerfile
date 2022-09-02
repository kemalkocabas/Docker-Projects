FROM node:14-slim
WORKDIR /vue-app
COPY app/ .
RUN npm install
RUN npm run build
RUN npm install -g live-server
EXPOSE 8080
CMD ["live-server", "dist/"]