file(GLOB SOURCES *
        )


idf_component_register(
        SRCS ${SOURCES}
        INCLUDE_DIRS "."
        REQUIRES json request_runner
)
