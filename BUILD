package(default_visibility = ["//visibility:public"])

cc_library(
    name = "lager",
    hdrs = glob([
        "lager/**/*.hpp",
    ]),
    includes = [
        ".",
        "lager/",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "@boost.hana",
        "@boost.intrusive",
        "@cereal",
        "@immer",
        "@zug",
    ],
)
