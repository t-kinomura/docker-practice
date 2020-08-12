#ENTRYPOINTとCMD

#ENTRYPOINTはrun時に上書きできない。run時に上書きできるのはCMDの部分のみ。
#ENTRYPOINTがある場合は、CMDはENTRYPOINTのパラメーターを指定する役割になる。
#run時にCMDで指定したパラメーターの部分を変更して使うことができる。
#コンテナをコマンドのようにして使いたいときにENTRYPOINTを使う。


FROM ubuntu:latest
RUN touch test
ENTRYPOINT ["ls"]
CMD ["--help"]
