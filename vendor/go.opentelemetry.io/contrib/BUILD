load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "contrib",
    srcs = [
        "contrib.go",
        "doc.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/go.opentelemetry.io/contrib",
    importpath = "go.opentelemetry.io/contrib",
    visibility = ["//visibility:public"],
)
