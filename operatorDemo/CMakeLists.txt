cmake_minimum_required(VERSION 3.2)

project(operatordemo)

aux_source_directory(. DIR_SRCS)

add_executable(operatordemo ${DIR_SRCS})
