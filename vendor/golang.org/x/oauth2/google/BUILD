load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "google",
    srcs = [
        "appengine.go",
        "appengine_gen2_flex.go",
        "default.go",
        "doc.go",
        "google.go",
        "jwt.go",
        "sdk.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/oauth2/google",
    importpath = "golang.org/x/oauth2/google",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/cloud.google.com/go/compute/metadata",
        "//vendor/golang.org/x/oauth2",
        "//vendor/golang.org/x/oauth2/authhandler",
        "//vendor/golang.org/x/oauth2/google/internal/externalaccount",
        "//vendor/golang.org/x/oauth2/internal",
        "//vendor/golang.org/x/oauth2/jws",
        "//vendor/golang.org/x/oauth2/jwt",
    ],
)
