# set variable
set(LIB_SRC hello.c)

# add to lib
add_library(libhello ${LIB_SRC})

# sets properties on targets
set_target_properties(libhello PROPERTIES OUTPUT_NAME "hello" PREFIX "")