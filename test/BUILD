cc_test(
    name = "test",
    srcs = [
        "cereal/immer_table.cpp",
        #      "cereal/immer_vector.cpp",
        "cereal/cerealize.hpp",
        #        "util.cpp",
        #        "errors.cpp",
    ],
    defines = [
        "CATCH_CONFIG_MAIN",
    ],
    linkstatic = True,
    deps = [
        "@catch2//:catch2_main",
        "@lager",
    ],
)
