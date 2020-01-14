cmake_minimum_required(VERSION 3.0)

project(stick_fight_the_game_handicap_helperxd)

find_package(OpenCV REQUIRED)

add_executable(stick_fight_the_game_handicap_helperxd main.cpp)

target_link_libraries(stick_fight_the_game_handicap_helperxd ${OpenCV_LIBS})

#install(TARGETS stick_fight_the_game_handicap_helperxd RUNTIME DESTINATION bin)
