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
        "@llvm-project//llvm:ExecutionEngine",
        "@llvm-project//llvm:Interpreter",
        "@llvm-project//llvm:Support",
        "@llvm-project//llvm:MC",
        "@llvm-project//llvm:X86CodeGen",
        "@llvm-project//llvm:X86AsmParser",
        "@llvm-project//llvm:ARMCodeGen",
        "@llvm-project//llvm:ARMAsmParser",
        "@llvm-project//llvm:OrcJIT",
    ],
)
