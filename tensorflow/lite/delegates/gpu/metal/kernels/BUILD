load(
    "//tensorflow/core/platform:build_config_root.bzl",
    "tf_gpu_tests_tags",
)

package(
    # copybara:uncomment default_applicable_licenses = ["//tensorflow:license"],
    default_visibility = ["//visibility:public"],
    licenses = ["notice"],
)

objc_library(
    name = "add_test_lib",
    testonly = 1,
    srcs = ["add_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:add_test_util",
    ],
)

objc_library(
    name = "cast_test_lib",
    testonly = 1,
    srcs = ["cast_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common:status",
        "//tensorflow/lite/delegates/gpu/common/tasks:cast_test_util",
    ],
)

objc_library(
    name = "concat_test_lib",
    testonly = 1,
    srcs = ["concat_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:concat_test_util",
    ],
)

objc_library(
    name = "conv_test_lib",
    testonly = 1,
    srcs = ["conv_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common:operations",
        "//tensorflow/lite/delegates/gpu/common:shape",
        "//tensorflow/lite/delegates/gpu/common:status",
        "//tensorflow/lite/delegates/gpu/common:tensor",
        "//tensorflow/lite/delegates/gpu/common:util",
        "//tensorflow/lite/delegates/gpu/common/tasks:conv_constants_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:conv_generic",
        "//tensorflow/lite/delegates/gpu/common/tasks:conv_generic_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:conv_metal_simd",
        "//tensorflow/lite/delegates/gpu/common/tasks:winograd",
        "//tensorflow/lite/delegates/gpu/metal:compute_task",
        "//tensorflow/lite/delegates/gpu/metal:metal_spatial_tensor",
    ],
)

objc_library(
    name = "conv_weights_converter_test_lib",
    testonly = 1,
    srcs = ["conv_weights_converter_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:conv_weights_converter_test_util",
    ],
)

objc_library(
    name = "cumsum_test_lib",
    testonly = 1,
    srcs = ["cumsum_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common:status",
        "//tensorflow/lite/delegates/gpu/common/tasks:cumsum_test_util",
    ],
)

objc_library(
    name = "depthwise_conv_test_lib",
    testonly = 1,
    srcs = ["depthwise_conv_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:depthwise_conv_3x3_stride_h2_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:depthwise_conv_3x3_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:depthwise_conv_test_util",
    ],
)

objc_library(
    name = "elementwise_test_lib",
    testonly = 1,
    srcs = ["elementwise_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common:status",
        "//tensorflow/lite/delegates/gpu/common/tasks:elementwise_test_util",
    ],
)

objc_library(
    name = "fully_connected_test_lib",
    testonly = 1,
    srcs = ["fully_connected_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:fully_connected_test_util",
    ],
)

objc_library(
    name = "gather_test_lib",
    testonly = 1,
    srcs = ["gather_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:gather_test_util",
    ],
)

objc_library(
    name = "lstm_test_lib",
    testonly = 1,
    srcs = ["lstm_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:lstm_test_util",
    ],
)

objc_library(
    name = "max_unpooling_test_lib",
    testonly = 1,
    srcs = ["max_unpooling_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:max_unpooling_test_util",
    ],
)

objc_library(
    name = "mean_stddev_normalization_test_lib",
    testonly = 1,
    srcs = ["mean_stddev_normalization_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:mean_stddev_normalization_test_util",
    ],
)

objc_library(
    name = "one_hot_test_lib",
    testonly = 1,
    srcs = ["one_hot_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common:status",
        "//tensorflow/lite/delegates/gpu/common/tasks:one_hot_test_util",
    ],
)

objc_library(
    name = "padding_test_lib",
    testonly = 1,
    srcs = ["padding_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:padding_test_util",
    ],
)

objc_library(
    name = "pooling_test_lib",
    testonly = 1,
    srcs = ["pooling_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:pooling_test_util",
    ],
)

objc_library(
    name = "prelu_test_lib",
    testonly = 1,
    srcs = ["prelu_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:prelu_test_util",
    ],
)


objc_library(
    name = "quantize_and_dequantize_test_lib",
    testonly = 1,
    srcs = ["quantize_and_dequantize_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common:operations",
        "//tensorflow/lite/delegates/gpu/common:shape",
        "//tensorflow/lite/delegates/gpu/common:status",
        "//tensorflow/lite/delegates/gpu/common:tensor",
        "//tensorflow/lite/delegates/gpu/common:util",
        "//tensorflow/lite/delegates/gpu/common/tasks:quantize_and_dequantize_test_util",
    ],
)

objc_library(
    name = "reduce_test_lib",
    testonly = 1,
    srcs = ["reduce_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:reduce_test_util",
    ],
)

objc_library(
    name = "relu_test_lib",
    testonly = 1,
    srcs = ["relu_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:relu_test_util",
    ],
)

objc_library(
    name = "resampler_test_lib",
    testonly = 1,
    srcs = ["resampler_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        "//tensorflow/lite/delegates/gpu/common:shape",
        "//tensorflow/lite/delegates/gpu/common:status",
        "//tensorflow/lite/delegates/gpu/common/tasks:resampler_test_util",
        "//tensorflow/lite/delegates/gpu/metal/kernels:test_util",
    ],
)

objc_library(
    name = "resize_test_lib",
    testonly = 1,
    srcs = ["resize_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:resize_test_util",
    ],
)

objc_library(
    name = "reshape_test_lib",
    testonly = 1,
    srcs = ["reshape_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:reshape_test_util",
    ],
)

objc_library(
    name = "select_v2_test_lib",
    testonly = 1,
    srcs = ["select_v2_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:select_v2_test_util",
    ],
)

objc_library(
    name = "slice_test_lib",
    testonly = 1,
    srcs = ["slice_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:strided_slice_test_util",
    ],
)

objc_library(
    name = "softmax_test_lib",
    testonly = 1,
    srcs = ["softmax_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:softmax_test_util",
    ],
)

objc_library(
    name = "space_to_depth_test_lib",
    testonly = 1,
    srcs = ["space_to_depth_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common:status",
        "//tensorflow/lite/delegates/gpu/common/tasks:space_to_depth_test_util",
    ],
)

objc_library(
    name = "split_test_lib",
    testonly = 1,
    srcs = ["split_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:split_test_util",
    ],
)

objc_library(
    name = "tile_test_lib",
    testonly = 1,
    srcs = ["tile_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:tile_test_util",
    ],
)


objc_library(
    name = "transpose_conv_test_lib",
    testonly = 1,
    srcs = ["transpose_conv_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:convolution_transposed_3x3_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:convolution_transposed_3x3_thin_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:convolution_transposed_4x4_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:convolution_transposed_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:convolution_transposed_thin_test_util",
    ],
)

objc_library(
    name = "transpose_test_lib",
    testonly = 1,
    srcs = ["transpose_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:transpose_test_util",
    ],
)

objc_library(
    name = "test_util",
    testonly = 1,
    srcs = [
        "test_util.cc",
    ],
    hdrs = ["test_util.h"],
    copts = [
        "-ObjC++",
    ],
    sdk_frameworks = ["Metal"],
    deps = [
        "//tensorflow/lite/delegates/gpu/common:convert",
        "//tensorflow/lite/delegates/gpu/common:gpu_info",
        "//tensorflow/lite/delegates/gpu/common:precision",
        "//tensorflow/lite/delegates/gpu/common:shape",
        "//tensorflow/lite/delegates/gpu/common:status",
        "//tensorflow/lite/delegates/gpu/common:tensor",
        "//tensorflow/lite/delegates/gpu/common:types",
        "//tensorflow/lite/delegates/gpu/common:util",
        "//tensorflow/lite/delegates/gpu/common/task:gpu_operation",
        "//tensorflow/lite/delegates/gpu/common/task:testing_util",
        "//tensorflow/lite/delegates/gpu/metal:compute_task",
        "//tensorflow/lite/delegates/gpu/metal:metal_device",
        "//tensorflow/lite/delegates/gpu/metal:metal_spatial_tensor",
        "@com_google_absl//absl/strings",
    ],
)

objc_library(
    name = "winograd_test_lib",
    testonly = 1,
    srcs = ["winograd_test.mm"],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common:winograd_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:winograd_test_util",
    ],
)

objc_library(
    name = "kernel_tests_lib",
    testonly = 1,
    srcs = [
        "add_test.mm",
        "cast_test.mm",
        "concat_test.mm",
        "conv_test.mm",
        "conv_weights_converter_test.mm",
        "cumsum_test.mm",
        "depthwise_conv_test.mm",
        "elementwise_test.mm",
        "fully_connected_test.mm",
        "gather_test.mm",
        "lstm_test.mm",
        "max_unpooling_test.mm",
        "mean_stddev_normalization_test.mm",
        "one_hot_test.mm",
        "padding_test.mm",
        "pooling_test.mm",
        "prelu_test.mm",
        "quantize_and_dequantize_test.mm",
        "reduce_test.mm",
        "relu_test.mm",
        "resampler_test.mm",
        "reshape_test.mm",
        "resize_test.mm",
        "select_v2_test.mm",
        "slice_test.mm",
        "softmax_test.mm",
        "space_to_depth_test.mm",
        "split_test.mm",
        "tile_test.mm",
        "transpose_conv_test.mm",
        "transpose_test.mm",
        "winograd_test.mm",
    ],
    hdrs = [
    ],
    sdk_frameworks = ["XCTest"],
    deps = [
        ":test_util",
        "//tensorflow/lite/delegates/gpu/common:operations",
        "//tensorflow/lite/delegates/gpu/common:shape",
        "//tensorflow/lite/delegates/gpu/common:status",
        "//tensorflow/lite/delegates/gpu/common:tensor",
        "//tensorflow/lite/delegates/gpu/common:util",
        "//tensorflow/lite/delegates/gpu/common/tasks:add_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:cast_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:concat_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:conv_constants_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:conv_generic",
        "//tensorflow/lite/delegates/gpu/common/tasks:conv_generic_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:conv_metal_simd",
        "//tensorflow/lite/delegates/gpu/common/tasks:conv_weights_converter_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:convolution_transposed_3x3_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:convolution_transposed_3x3_thin_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:convolution_transposed_4x4_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:convolution_transposed_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:convolution_transposed_thin_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:cumsum_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:depthwise_conv_3x3_stride_h2_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:depthwise_conv_3x3_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:depthwise_conv_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:elementwise_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:fully_connected_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:gather_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:lstm_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:max_unpooling_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:mean_stddev_normalization_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:one_hot_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:padding_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:pooling_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:prelu_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:quantize_and_dequantize_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:reduce_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:relu_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:resampler_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:reshape_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:resize_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:select_v2_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:softmax_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:space_to_depth_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:split_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:strided_slice_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:tile_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:transpose_test_util",
        "//tensorflow/lite/delegates/gpu/common/tasks:winograd",
        "//tensorflow/lite/delegates/gpu/common/tasks:winograd_test_util",
        "//tensorflow/lite/delegates/gpu/metal:compute_task",
        "//tensorflow/lite/delegates/gpu/metal:metal_spatial_tensor",
    ],
)

tflite_portable_test_suite()

