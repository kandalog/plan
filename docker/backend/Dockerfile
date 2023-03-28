FROM node:18.14.2-buster

WORKDIR /usr/src/app

COPY ./backend/package*.json ./

RUN npm install -g npm && npm install
# 本番環境用の場合
# RUN npm install --only=production

COPY ./backend .

# CMD ["npm", "start"]