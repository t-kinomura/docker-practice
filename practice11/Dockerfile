FROM ubuntu:latest
# RUN mkdir sample_folder
WORKDIR /sample_folder
RUN touch sample_file

#基本的に全てのコマンドはrootで実行される

# RUN mkdir sample_folder
# RUN cd sample_folder
# RUN touch sample_file

#この場合、sample_fileはrootに作成されてしまう。&&でつないだ場合はsample_folder配下に作成される。
#また、WORKDIRはそのディレクトリがなかったら作成してくれるので、その前のmkdirは不要。
