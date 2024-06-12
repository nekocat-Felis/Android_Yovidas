# Android NDK + CMake で Android APK を作るための Dockerfile.

# author nekocat-Felis
# date 2024/06/13

FROM ubuntu:latest
 
RUN \
    # ツールのインストール.
    apt update \
 && apt install doxygen cmake curl git unzip -y \
 && apt clean \
 && rm -rf /var/lib/apt/lists/* \
    # Android NDK のインストール.
 && curl -L https://dl.google.com/android/repository/android-ndk-r26d-linux.zip?hl=ja -o android-ndk-r26d-linux.zip \
 && unzip android-ndk-r26d-linux.zip -d home \
 && rm android-ndk-r26d-linux.zip