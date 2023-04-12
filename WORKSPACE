load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "com_google_googletest",
    sha256 = "730215d76eace9dd49bf74ce044e8daa065d175f1ac891cc1d6bb184ef94e565",
    strip_prefix = "googletest-f53219cdcb7b084ef57414efea92ee5b71989558",
    urls = [
        "https://github.com/google/googletest/archive/f53219cdcb7b084ef57414efea92ee5b71989558.tar.gz" # 2023-03-16
    ],
)

load("@com_google_googletest//:googletest_deps.bzl", "googletest_deps")

googletest_deps()

http_archive(
    name = "com_google_protobuf",
    strip_prefix = "protobuf-22.2",
    #urls = ["https://github.com/protocolbuffers/protobuf/archive/v3.11.3.tar.gz"],
    urls = ["https://github.com/protocolbuffers/protobuf/releases/download/v22.2/protobuf-22.2.tar.gz"]
)

load("@com_google_protobuf//:protobuf_deps.bzl", "protobuf_deps")
protobuf_deps()
