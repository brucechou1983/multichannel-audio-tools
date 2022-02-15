# reference from MediaPipe repo
package(default_visibility = ["//visibility:public"])

cc_library(
    name = "glog",
    visibility = ["//visibility:public"],
    deps = select({
        "//mediapipe:android_x86": [
            "@com_github_glog_glog_no_gflags//:glog",
        ],
        "//mediapipe:android_x86_64": [
            "@com_github_glog_glog_no_gflags//:glog",
        ],
        "//mediapipe:android_armeabi": [
            "@com_github_glog_glog_no_gflags//:glog",
        ],
        "//mediapipe:android_arm": [
            "@com_github_glog_glog_no_gflags//:glog",
        ],
        "//mediapipe:android_arm64": [
            "@com_github_glog_glog_no_gflags//:glog",
        ],
        "//mediapipe:ios": [
            "@com_github_glog_glog_no_gflags//:glog",
        ],
        "//mediapipe:macos": [
            "@com_github_glog_glog//:glog",
        ],
        "//mediapipe:windows": [
            "@com_github_glog_glog//:glog",
        ],
        "//conditions:default": [
            "@com_github_glog_glog//:glog",
        ],
    }),
)
