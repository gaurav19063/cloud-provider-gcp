load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "internal",
    srcs = [
        "go_runtime_metrics.go",
        "metric.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/prometheus/client_golang/prometheus/internal",
    importpath = "github.com/prometheus/client_golang/prometheus/internal",
    visibility = ["//vendor/github.com/prometheus/client_golang/prometheus:__subpackages__"],
    deps = [
        "//vendor/github.com/prometheus/client_model/go",
        "//vendor/github.com/prometheus/common/model",
    ],
)
