load("@com_github_bazelbuild_buildtools//buildifier:def.bzl", "buildifier")

buildifier(name = "buildifier")

cc_binary(
    name = "toy_main",
    srcs = [
        "KaleidoscopeJIT.h",
        "main.cc",
    ],
    deps = [
        "@llvm-project//llvm:Core",
        "@llvm-project//llvm:OrcJIT",
    ],
)
