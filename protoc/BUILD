load("@rules_cc//cc:defs.bzl", "cc_proto_library")
load("@rules_proto//proto:defs.bzl", "proto_library")

cc_proto_library(
    name = "adressbook_cc_pb",
    deps = [":addressbook_pb"]
)

proto_library(
    name = "addressbook_pb",
    srcs = ["addressbook.proto"],
)

package(default_visibility = ["//visibility:public"])