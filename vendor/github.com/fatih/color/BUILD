load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "color",
    srcs = [
        "color.go",
        "doc.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/fatih/color",
    importpath = "github.com/fatih/color",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/mattn/go-colorable",
        "//vendor/github.com/mattn/go-isatty",
    ],
)
