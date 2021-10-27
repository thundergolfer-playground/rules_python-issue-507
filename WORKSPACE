load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "rules_python",
    url = "https://github.com/bazelbuild/rules_python/releases/download/0.5.0/rules_python-0.5.0.tar.gz",
    sha256 = "",
)

# I shouldn't have to do this: https://github.com/bazelbuild/rules_python/issues/497
load("@rules_python//python/pip_install:repositories.bzl", "pip_install_dependencies")
pip_install_dependencies()