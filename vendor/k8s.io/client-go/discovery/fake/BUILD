load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "fake",
    srcs = ["discovery.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/discovery/fake",
    importpath = "k8s.io/client-go/discovery/fake",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/gnostic/openapiv2",
        "//vendor/k8s.io/apimachinery/pkg/api/errors",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/version",
        "//vendor/k8s.io/client-go/openapi",
        "//vendor/k8s.io/client-go/pkg/version",
        "//vendor/k8s.io/client-go/rest",
        "//vendor/k8s.io/client-go/testing",
    ],
)
