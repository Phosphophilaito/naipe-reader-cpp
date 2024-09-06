cmake_minimum_required(VERSION 3.10)
project(Naipe-Reader-cpp)

set(OpenCV_DIR D:/openCV/)
find_package(OpenCV REQUIRED)
target_link_libraries(${PROJECT_NAME} ${OpenCV_LIBS})