cmake_minimum_required(VERSION 3.10)
project(ClassroomProject)

# Настройка стандарта C++
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Добавление исполняемого файла из исходника
add_executable(ClassroomProject src/main.cpp)

# Если добавляете тесты, раскомментируйте блок ниже:
# enable_testing()
# find_package(GTest REQUIRED)
# include_directories(${GTEST_INCLUDE_DIRS})
# add_executable(tests tests/unit_tests.cpp)
# target_link_libraries(tests ${GTEST_LIBRARIES} pthread)
# add_test(NAME unit_tests COMMAND tests)
