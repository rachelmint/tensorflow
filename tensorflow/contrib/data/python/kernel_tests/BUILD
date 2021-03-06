package(default_visibility = ["//tensorflow:internal"])

licenses(["notice"])  # Apache 2.0

exports_files(["LICENSE"])

load("//tensorflow:tensorflow.bzl", "py_test")

py_test(
    name = "iterator_ops_test",
    size = "small",
    srcs = ["iterator_ops_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/core:protos_all_py",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:constant_op",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//tensorflow/python:framework_ops",
        "//tensorflow/python:gradients",
        "//tensorflow/python:math_ops",
        "//tensorflow/python:training",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "batch_dataset_op_test",
    size = "small",
    srcs = ["batch_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:constant_op",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//tensorflow/python:math_ops",
        "//tensorflow/python:sparse_tensor",
        "//tensorflow/python:string_ops",
        "//tensorflow/python:tensor_shape",
        "//tensorflow/python:util",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "bucketing_test",
    size = "small",
    srcs = ["bucketing_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:constant_op",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//tensorflow/python:framework_ops",
        "//tensorflow/python:math_ops",
        "//tensorflow/python:string_ops",
        "//tensorflow/python:tensor_shape",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "dataset_constructor_op_test",
    size = "small",
    srcs = ["dataset_constructor_op_test.py"],
    srcs_version = "PY2AND3",
    tags = [
        "manual",
        "nomac",  # b/62040583
    ],
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//tensorflow/python:math_ops",
        "//tensorflow/python:sparse_tensor",
        "//tensorflow/python:util",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "filter_dataset_op_test",
    size = "small",
    srcs = ["filter_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//tensorflow/python:math_ops",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "flat_map_dataset_op_test",
    size = "small",
    srcs = ["flat_map_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//tensorflow/python:training",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "list_files_dataset_op_test",
    size = "small",
    srcs = ["list_files_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//tensorflow/python:util",
    ],
)

py_test(
    name = "map_dataset_op_test",
    size = "small",
    srcs = ["map_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:constant_op",
        "//tensorflow/python:data_flow_ops",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//tensorflow/python:io_ops",
        "//tensorflow/python:lookup_ops",
        "//tensorflow/python:math_ops",
        "//tensorflow/python:random_ops",
        "//tensorflow/python:script_ops",
        "//tensorflow/python:string_ops",
        "//tensorflow/python:util",
        "//tensorflow/python:variable_scope",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "range_dataset_op_test",
    size = "small",
    srcs = ["range_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:constant_op",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//tensorflow/python:tensor_shape",
    ],
)

py_test(
    name = "reader_dataset_ops_test",
    size = "small",
    srcs = ["reader_dataset_ops_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/core:protos_all_py",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:constant_op",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//tensorflow/python:framework_ops",
        "//tensorflow/python:lib",
        "//tensorflow/python:parsing_ops",
        "//tensorflow/python:util",
    ],
)

py_test(
    name = "resample_test",
    size = "medium",
    srcs = ["resample_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:errors",
        "//tensorflow/python:string_ops",
        "//tensorflow/python:util",
        "//tensorflow/python:variables",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "sequence_dataset_op_test",
    size = "small",
    srcs = ["sequence_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "shuffle_dataset_op_test",
    size = "small",
    srcs = ["shuffle_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:constant_op",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "shard_dataset_op_test",
    size = "small",
    srcs = ["shard_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:errors",
    ],
)

py_test(
    name = "cache_dataset_op_test",
    size = "small",
    srcs = ["cache_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:constant_op",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//tensorflow/python:variables",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "zip_dataset_op_test",
    size = "small",
    srcs = ["zip_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/python:array_ops",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:dtypes",
        "//tensorflow/python:errors",
        "//third_party/py/numpy",
    ],
)

py_test(
    name = "concatenate_dataset_op_test",
    size = "small",
    srcs = ["concatenate_dataset_op_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/contrib/data/python/ops:dataset_ops",
        "//tensorflow/contrib/data/python/util:nest",
        "//tensorflow/python:client_testlib",
        "//tensorflow/python:errors",
        "//tensorflow/python:tensor_shape",
        "//third_party/py/numpy",
    ],
)

filegroup(
    name = "all_files",
    srcs = glob(
        ["**/*"],
        exclude = [
            "**/METADATA",
            "**/OWNERS",
        ],
    ),
    visibility = ["//tensorflow:__subpackages__"],
)
