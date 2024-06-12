FROM golang:alpine

RUN apk update
RUN apk add alpine-sdk

# 作業ディレクトリを設定
WORKDIR /app/go

# ソースコードをコンテナにコピー
COPY ./go-app ./

# アプリケーションをビルド
RUN go build -o main .

# コンテナ起動時に実行されるコマンド
CMD [ "/app/go/main" ]