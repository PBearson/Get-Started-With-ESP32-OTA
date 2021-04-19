# Get Started With ESP32 OTA

## Introduction

This page is intended to guide users through the OTA procedure for the ESP32. All referenced projects come from the [ESP-IDF OTA examples directory](https://github.com/espressif/esp-idf/tree/master/examples/system/ota), with the exception of Hello World, which can be found [here](https://github.com/espressif/esp-idf/tree/master/examples/get-started/hello_world). The assumption is that you have set up ESP-IDF to version 4.* (e.g., 4.2).

The purpose of OTA is to update the firmware of an IoT device (such as ESP32) remotely and without user interaction. The ESP32 OTA mechanism supports HTTPS to securely transmit firmware over the network. The OTA mechanism can also check the version of the firmware and compare it with the current version. Then the device may only load the new firmware if it is newer than the current version — a feature known as "anti-rollback".

## Prepare the OTA Firmware Images

## Start the Web Server

## Run the simple_ota_example Project

## Run the native_ota_example Project

## Run the advanced_https_ota Project
