# clion-swift-CMakeLists
swift CMakelists file for CLion



cmake_minimum_required(VERSION 3.11)
project(csvconf)

add_custom_target(csvconf ALL
        COMMAND /home/peer/.swiftenv/versions/4.1/usr/bin/swift build
        WORKING_DIRECTORY ${CMAKE_SOURCE_DIR}
        SOURCES .build/checkouts
        SOURCES Sources)
