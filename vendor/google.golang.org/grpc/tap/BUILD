load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "tap",
    srcs = ["tap.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/tap",
    importpath = "google.golang.org/grpc/tap",
    visibility = ["//visibility:public"],
)
