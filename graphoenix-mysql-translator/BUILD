load("@rules_java//java:defs.bzl", "java_binary", "java_library", "java_test")

package(default_visibility = ["//visibility:public"])

java_library(
    name = "mysql-translator",
    srcs = glob(["src/main/java/io/graphoenix/mysql/translator/*.java"]),
    deps = ["//graphoenix-antlr",
            "@maven//:com_github_jsqlparser_jsqlparser",
            "@maven//:com_google_guava_guava"],
)
