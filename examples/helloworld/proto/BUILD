package(default_visibility = ["//visibility:public"])

load("//java:rules.bzl", "java_proto_library")

filegroup(
    name = "protos",
    srcs = ["helloworld.proto"],
)

java_proto_library(
    name = "java",
    proto_deps = [
        "//examples/proto:java",
    ],
    protos = [":protos"],
    verbose = 0,
    with_grpc = True,
)
