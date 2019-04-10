workspace(name = "org_pubref_rules_protobuf")

load("//protobuf:rules.bzl", "github_archive")
load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

load("//java:rules.bzl", "java_proto_repositories", "nano_proto_repositories")

java_proto_repositories()
nano_proto_repositories()

load("//protobuf:rules.bzl", "proto_repositories")

proto_repositories()
