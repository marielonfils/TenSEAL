package(default_visibility = ["//visibility:public"])

py_library(
    name = "tenseal_tensors",
    srcs = [
        "__init__.py",
        "abstract_tensor.py",
        "bfvvector.py",
        "bfvtensor.py",
        "ckkstensor.py",
        "ckksvector.py",
        "plaintensor.py",
        "plaintextvector.py",
    ],
    data = ["//tenseal:_tenseal_cpp.so"],
    srcs_version = "PY3",
    visibility = ["//visibility:public"],
)
