# Set all target’s visibility in this package to "public".
package(default_visibility = ["//visibility:public"])

# Load rules_haskell rules.
load(
    "@rules_haskell//haskell:defs.bzl",
    "haskell_binary",
    "haskell_library",
)
load(
    "@euler//:euler.bzl",
    "euler_test",
)

haskell_library(
    name = "helpers",
    srcs = ["helpers.hs"],
    deps = ["//:base"],
)
