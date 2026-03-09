# Adafruit MAX31865 Library
# https://github.com/adafruit/Adafruit_31865
# MIT License

cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_MAX31865.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES arduino-esp32)

project(Adafruit_MAX31865)
