package(
    default_visibility = [
        "//src:__subpackages__",
    ],
)

java_library(
    name = "worker",
    srcs = glob(["*.java"]),
    deps = [
        "//src/main/java:actions",
        "//src/main/java:buildtool-runtime",
        "//src/main/java:common",
        "//src/main/java:concurrent",
        "//src/main/java:options",
        "//src/main/java:vfs",
        "//src/main/protobuf:proto_worker_protocol",
        "//third_party:apache_commons_pool2",
        "//third_party:guava",
        "//third_party:jsr305",
    ],
)

filegroup(
    name = "srcs",
    srcs = glob(["**"]),
    visibility = ["//src/main/java:__pkg__"],
)
