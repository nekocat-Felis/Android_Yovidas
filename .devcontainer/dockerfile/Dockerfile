# android_ndk_cmake
FROM ubuntu:latest

RUN apt update \
 && apt install doxygen cmake curl git -y \
 && apt clean \
 && rm -rf /var/lib/apt/lists/* \
 && curl -L https://dl.google.com/android/repository/android-ndk-r26d-linux.zip?hl=ja -o android-ndk-r26d-linux.zip \
 && unzip android-ndk-r26d-linux.zip -d home \
 && rm android-ndk-r26d-linux.zip