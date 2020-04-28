set(HEADER_FILES
  include/glad/glad.h
  include/KHR/khrplatform.h
)

set(SOURCE_FILES
  src/glad.c
)

add_library(glad STATIC ${HEADER_FILES} ${SOURCE_FILES})
target_include_directories(glad PUBLIC include)