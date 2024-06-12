# android_ndk_cmake
FROM ubuntu:latest

RUN apt update \
 && apt install doxygen cmake curl -y \
 && apt clean \
 && rm -rf /var/lib/apt/lists/* \
 && curl -O https://dl.google.com/android/repository/android-ndk-r26d-linux.zip?hl=ja