# Description:
#   Contains Keras integration tests that verify with other TF high level APIs.

load("//tensorflow:tensorflow.bzl", "tf_py_test")

package(
    default_visibility = [
        "//tensorflow/tools/pip_package:__pkg__",
    ],
    licenses = ["notice"],  # Apache 2.0
)

exports_files(["LICENSE"])

tf_py_test(
    name = "forwardprop_test",
    srcs = ["forwardprop_test.py"],
    python_version = "PY3",
    deps = [
        "//tensorflow:tensorflow_py",
        "//tensorflow/python:extra_py_tests_deps",
    ],
)

tf_py_test(
    name = "function_test",
    srcs = ["function_test.py"],
    python_version = "PY3",
    deps = [
        "//tensorflow:tensorflow_py",
        "//tensorflow/python:extra_py_tests_deps",
    ],
)

tf_py_test(
    name = "legacy_rnn_test",  # Remove this target in when TF 1 is deprecated.
    srcs = ["legacy_rnn_test.py"],
    python_version = "PY3",
    deps = [
        "//tensorflow:tensorflow_py",
        "//tensorflow/python:extra_py_tests_deps",
    ],
)
