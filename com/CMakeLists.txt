target_include_directories(${CMAKE_PROJECT_NAME} PUBLIC include)
target_sources(${CMAKE_PROJECT_NAME} PUBLIC
        ${CMAKE_CURRENT_LIST_DIR}/DataSourceSensor.cpp
        ${CMAKE_CURRENT_LIST_DIR}/DataDestinationCentral.cpp)
