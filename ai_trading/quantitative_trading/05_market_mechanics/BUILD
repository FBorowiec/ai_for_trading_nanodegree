load("@rules_python//python:defs.bzl", "py_binary")
load("@ai_for_trading_deps//:requirements.bzl", "requirement")

py_binary(
    name = "resample_data",
    srcs = [
        "quiz_tests.py",
        "resample_data.py",
        "tests.py",
    ],
    deps = [
        requirement("pandas"),
        requirement("numpy"),
    ],
)
