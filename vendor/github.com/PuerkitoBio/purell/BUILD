load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "purell",
    srcs = ["purell.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/PuerkitoBio/purell",
    importpath = "github.com/PuerkitoBio/purell",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/PuerkitoBio/urlesc",
        "//vendor/golang.org/x/net/idna",
        "//vendor/golang.org/x/text/unicode/norm",
        "//vendor/golang.org/x/text/width",
    ],
)
