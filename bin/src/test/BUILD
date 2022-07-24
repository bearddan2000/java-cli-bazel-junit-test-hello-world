load("@rules_java//java:defs.bzl", "java_test")

java_test (
    name = "BazelApp",
    srcs = glob(["java/**/*.java"]),
    test_class = "example.TestMain",
    deps = [
      "@maven//:junit_junit",
      "//src/main:hello-lib"
    ],
)
