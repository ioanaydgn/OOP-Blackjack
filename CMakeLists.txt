cmake_minimum_required(VERSION 3.25)
project(BlackJack)


set(CMAKE_BUILD_TYPE Debug)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14")
add_executable(
        BlackJack
        blackjack.cpp
        card.cpp
        dealer.cpp
        deck.cpp
        game.cpp
        human.cpp
        player.cpp
        print.cpp
        statistics.cpp
)
