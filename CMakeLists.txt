cmake_minimum_required(VERSION 3.22)

project(BNO055_SensorAPI)

add_library(BNO055_SensorAPI STATIC
  "bno055.c"
)

target_include_directories(BNO055_SensorAPI
  PUBLIC
    ""
)
