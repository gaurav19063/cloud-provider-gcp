load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "value",
    srcs = [
        "name.go",
        "pointer_unsafe.go",
        "sort.go",
        "zero.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/google/go-cmp/cmp/internal/value",
    importpath = "github.com/google/go-cmp/cmp/internal/value",
    visibility = ["//vendor/github.com/google/go-cmp/cmp:__subpackages__"],
)
