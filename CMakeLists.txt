cmake_minimum_required(VERSION 3.9)
project(TravelingSalesmanCpp)

set(CMAKE_CXX_STANDARD 17)

add_executable(TravelingSalesmanCpp headers/Point.h src/main.cpp headers/IPathSolver.h src/BruteforceSolver.cpp headers/BruteforceSolver.h src/GreedySolver.cpp headers/GreedySolver.h headers/SolverResult.h src/Point.cpp headers/City.h src/CitySeed.cpp headers/CitySeed.h src/Drawer.cpp headers/Drawer.h)

target_link_libraries(TravelingSalesmanCpp GL)
target_link_libraries(TravelingSalesmanCpp glut)

