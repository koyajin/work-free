FROM node:16.18.1

# 作業ディレクトリを設定
WORKDIR /app/react

# ソースコードをコンテナにコピー
COPY ./react-app/package.json ./

# モジュールインストール
RUN npm i

CMD ["npm","start"]