cmake_minimum_required(VERSION 3.22.1) # объявляем минимальную версию cmake
project(Task_3.cpp) # устанавливаем имя проекта
set(SOURCES Task_3.cpp) # переменной SOURCES присваиваем значение 
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS}" -fsanitizer=address -g " )
add_executable(Task_3.cpp ${SOURCES})

