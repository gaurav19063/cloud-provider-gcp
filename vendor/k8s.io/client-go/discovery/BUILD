load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "discovery",
    srcs = [
        "discovery_client.go",
        "doc.go",
        "helper.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/discovery",
    importpath = "k8s.io/client-go/discovery",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto",
        "//vendor/github.com/google/gnostic/openapiv2",
        "//vendor/k8s.io/apimachinery/pkg/api/errors",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime",
        "//vendor/k8s.io/apimachinery/pkg/util/sets",
        "//vendor/k8s.io/apimachinery/pkg/version",
        "//vendor/k8s.io/client-go/kubernetes/scheme",
        "//vendor/k8s.io/client-go/openapi",
        "//vendor/k8s.io/client-go/rest",
    ],
)
