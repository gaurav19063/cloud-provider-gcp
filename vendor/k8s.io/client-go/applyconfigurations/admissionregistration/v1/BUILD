load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "admissionregistration",
    srcs = [
        "mutatingwebhook.go",
        "mutatingwebhookconfiguration.go",
        "rule.go",
        "rulewithoperations.go",
        "servicereference.go",
        "validatingwebhook.go",
        "validatingwebhookconfiguration.go",
        "webhookclientconfig.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/applyconfigurations/admissionregistration/v1",
    importpath = "k8s.io/client-go/applyconfigurations/admissionregistration/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/admissionregistration/v1:admissionregistration",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/util/managedfields",
        "//vendor/k8s.io/client-go/applyconfigurations/internal",
        "//vendor/k8s.io/client-go/applyconfigurations/meta/v1:meta",
    ],
)
