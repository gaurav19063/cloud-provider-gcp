load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "model",
    srcs = [
        "alert.go",
        "fingerprinting.go",
        "fnv.go",
        "labels.go",
        "labelset.go",
        "metric.go",
        "model.go",
        "signature.go",
        "silence.go",
        "time.go",
        "value.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/prometheus/common/model",
    importpath = "github.com/prometheus/common/model",
    visibility = ["//visibility:public"],
)
