load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
  name = "com_github_nelhage_rules_boost",
  commit = "0598ab9aa992d6ad45088b480e1bf4526ef4ad04",
  remote = "https://github.com/nelhage/rules_boost",
  shallow_since = "1687996800 +0800",
)
load("@com_github_nelhage_rules_boost//:boost/boost.bzl", "boost_deps")
boost_deps()
