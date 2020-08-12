#ベストプラクティス：Docker imageのLayer数は最小限にする
#Layerを作るのはRUN, COPY, ADDの３つ
#コマンドは&&でつなげる
#見やすくなるようにバックスラッシュで改行する

FROM ubuntu:latest
RUN apt-get update && apt-get install\
xxx \
xyz \
yyy \
zzz

#apt-get；ubuntuのパッケージをインストールするコマンド
