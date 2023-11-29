# goバージョン
FROM golang:1.21-alpine
# アップデートとgitのインストール
RUN apk update && apk add git
# コンテナ内にディレクトリを作成
RUN mkdir /go/src/solution_develop/
# ワーキングディレクトリの設定
WORKDIR /go/src/solution_develop/
# ホストのファイルをコンテナの作業ディレクトリにコピー
COPY ./ /go/src/solution_develop/