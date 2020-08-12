# FROM ubuntu:latest
# RUN apt-get update && apt-get install -y \
#     curl \
#     nginx

#ここに次のように新しいパッケージを追加すると時間がかかる

# RUN apt-get update && apt-get install -y \
#     curl \ 
#     cvs \
#     nginx

#メンテナンス時はキャッシュを使う方が良いので次のような書き方をする

# RUN apt-get update
# RUN apt-get install -y \
#     curl \
#     nginx
# RUN cvs

#こうすることでupdateとcurlとnginxはキャッシュが使える

#メンテナンスが終わって最終的には次のように書く

FROM ubuntu:latest
RUN apt-get update && apt-get install -y \
    curl \
    cvs \
    nginx
