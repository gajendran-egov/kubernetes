load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "availabilitysets.go",
        "client.go",
        "containerservices.go",
        "disks.go",
        "images.go",
        "loganalytics.go",
        "models.go",
        "resourceskus.go",
        "snapshots.go",
        "usage.go",
        "version.go",
        "virtualmachineextensionimages.go",
        "virtualmachineextensions.go",
        "virtualmachineimages.go",
        "virtualmachineruncommands.go",
        "virtualmachines.go",
        "virtualmachinescalesetextensions.go",
        "virtualmachinescalesetrollingupgrades.go",
        "virtualmachinescalesets.go",
        "virtualmachinescalesetvms.go",
        "virtualmachinesizes.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/github.com/Azure/azure-sdk-for-go/services/compute/mgmt/2017-12-01/compute",
    importpath = "github.com/Azure/azure-sdk-for-go/services/compute/mgmt/2017-12-01/compute",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/Azure/azure-sdk-for-go/version:go_default_library",
        "//vendor/github.com/Azure/go-autorest/autorest:go_default_library",
        "//vendor/github.com/Azure/go-autorest/autorest/azure:go_default_library",
        "//vendor/github.com/Azure/go-autorest/autorest/date:go_default_library",
        "//vendor/github.com/Azure/go-autorest/autorest/to:go_default_library",
        "//vendor/github.com/Azure/go-autorest/autorest/validation:go_default_library",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
