FROM ubuntu:latest
RUN mkdir /new_dir
COPY something /new_dir/

#docker contextのsomethingというファイルをnew_dir配下にコピーする



#COPYとADDの違い・使い分け

#単純にファイルやフォルダをコピーする場合はCOPYを使う
#tarの圧縮ファイルをコピーして解凍したいときはADDを使う
#docker contextの中の大きいファイルをdocker damonに持っていきたい場合は普通に持っていくと時間がかかるため圧縮した形で持っていく。
