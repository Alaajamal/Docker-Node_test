FROM ubuntu:18.04

RUN apt-get update -y && apt-get install -y

RUN apt-get -y install clang

COPY . /usr/src/cpp_test

WORKDIR /usr/src/cpp_test

RUN clang++ -o Test main.cpp

CMD [ "./Test" ]
