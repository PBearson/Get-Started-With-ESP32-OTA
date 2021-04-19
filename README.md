# Get Started With ESP32 OTA

## Introduction

This page is intended to guide users through the OTA procedure for the ESP32. All referenced projects come from the [ESP-IDF OTA examples directory](https://github.com/espressif/esp-idf/tree/master/examples/system/ota), with the exception of Hello World, which can be found [here](https://github.com/espressif/esp-idf/tree/master/examples/get-started/hello_world). The assumption is that you have set up ESP-IDF to version 4.* (e.g., 4.2).

The purpose of OTA is to update the firmware of an IoT device (such as ESP32) remotely and without user interaction. The ESP32 OTA mechanism supports HTTPS to securely transmit firmware over the network. The OTA mechanism can also check the security version of the firmware and compare it with the current version. Then the device may only load the new firmware if it the security version is newer than the current version — a feature known as "anti-rollback".

## Prepare the OTA Firmware Images

We are going to prepare 3 different versions of the "Hello World" firmware: 1) no version; 2) app version  without anti-rollback support; 3) app version 2 with anti-rollback support and security version 1.

### Unversioned App

Navigate to the "hello_world/" directory and run ```idf.py build```, which will build the "Hello World" binary. The binary will be generated in the "build/" directory, under the filename "hello-world.bin". To copy this image to our server directory, run ```cp build/hello-world.bin ../server/```.

### App Version 1

### App Version 2 / Security Version 1

## Start the Web Server

## Run the simple_ota_example Project

## Run the native_ota_example Project

## Run the advanced_https_ota Project
