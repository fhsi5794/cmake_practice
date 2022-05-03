# include
include_directories(${PROJECT_SOURCE_DIR}/libhello)

# set variable
set(APP_SRC main.c)

# add the executable
add_executable(ex2 ${APP_SRC})

# link lib
target_link_libraries(ex2 libhello)