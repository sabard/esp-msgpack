idf_component_register(SRC_DIRS "msgpack-c/src"
    INCLUDE_DIRS "msgpack-c/include")

target_compile_options(${COMPONENT_LIB} PRIVATE -DMSGPACK_ENDIAN_LITTLE_BYTE)
