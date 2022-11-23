cmake_minimum_required(VERSION 3.5)
project(mkfw C)

add_executable(mkfw main.c crc32.c)

target_include_directories(mkfw
        PRIVATE
        ${PROJECT_SOURCE_DIR}
        )