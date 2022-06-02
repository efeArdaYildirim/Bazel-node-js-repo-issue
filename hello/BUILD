load("@build_bazel_rules_nodejs//:index.bzl",'nodejs_binary')

nodejs_binary(
  name='hello',
  data = ['index.js','@npm//@bzl/world'],
  entry_point = 'index.js'
)