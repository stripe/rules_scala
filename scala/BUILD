load("//scala:scala_toolchain.bzl", "scala_toolchain")

toolchain_type(
    name = "toolchain_type",
    visibility = ["//visibility:public"]
)


scala_toolchain(
      name = 'default_toolchain_impl',
      scalacopts = [],
      visibility = ["//visibility:public"]
)


toolchain(
    name = 'default_toolchain',
    toolchain_type = '@io_bazel_rules_scala//scala:toolchain_type',
    toolchain = ':default_toolchain_impl',
    visibility = ["//visibility:public"]
)
