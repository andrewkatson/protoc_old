workspace(name = "protoc_old")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

# the base google protocol buffer code.
http_archive(
    name = "com_google_protobuf",
    strip_prefix = "protobuf-25.2",
    urls = ["https://github.com/protocolbuffers/protobuf/archive/v25.2.zip"],
    integrity = "sha256-3dD1Jx8xtUnvx06zkGHhQhMmU9XQQwcfzsJlvVcec8Q="
)

load("@com_google_protobuf//:protobuf_deps.bzl", "protobuf_deps")

protobuf_deps()