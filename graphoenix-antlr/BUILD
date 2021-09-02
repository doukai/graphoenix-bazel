java_library(
    name = "antlr",
    srcs = glob(["src/main/java/graphql/parser/antlr/*.java"]),
    deps = ["@maven//:org_antlr_antlr4_runtime"],
)

java_library(
    name = "antlr-manager",
    srcs = glob(["src/main/java/io/graphoenix/antlr/manager/*.java"]),
    deps = [":antlr"],
)

