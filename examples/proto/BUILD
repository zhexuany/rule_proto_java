package(default_visibility = ["//visibility:public"])

load("//java:rules.bzl", "java_proto_library")

filegroup(
    name = "protos",
    srcs = [
        "common.proto",
    ],
)

java_proto_library(
    name = "java",
    protos = [":protos"],
)

# This conflicts with outputs from other rules here but demonstrates
# how to generate multiple language outputs simultaneously.
#
# proto_compile(
#     name = "pluriproto",
#     protos = [":protos"],
#     langs = [
#         "//ruby",
#         "//java",
#         "//java:nano",
#         "//python",
#         "//cpp",
#         "//objc",
#         "//closure",
#         "//csharp",
#         "//go",
#         "//node",
#     ],
#     verbose = 2,
#     with_grpc = True,
# )
