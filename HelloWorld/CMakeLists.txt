project(helloworld)

add_executable(helloworld main.cpp)

install(TARGETS helloworld RUNTIME DESTINATION bin)
