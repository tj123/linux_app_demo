cmake_minimum_required(VERSION 3.23)
project(linux_app_demo)

set(CMAKE_CXX_STANDARD 14)

add_subdirectory(base_api)
add_subdirectory(character_api)
add_subdirectory(epoll)
add_subdirectory(fifo)
add_subdirectory(file_io)
add_subdirectory(fork)
add_subdirectory(msg_queue)
add_subdirectory(phtread)
add_subdirectory(system_env)