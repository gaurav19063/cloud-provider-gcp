load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "cert",
    srcs = ["default_cert.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/api/transport/cert",
    importpath = "google.golang.org/api/transport/cert",
    visibility = ["//visibility:public"],
)
