load("@rules_cc//cc:defs.bzl", "cc_proto_library") 
load("@rules_proto//proto:defs.bzl", "proto_library") 

cc_binary( 
    name = "write", 
    srcs = ["write.cc"], 
    deps = [ 
        "//protoc:adressbook_cc_pb", 
    ], 
) 

cc_binary(
    name = "read",
    srcs = ["read.cc"],
    deps = [
        "//protoc:adressbook_cc_pb",
    ]
)