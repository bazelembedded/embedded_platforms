# [Bazel Embedded Platforms](bazel.build)

This repository houses a set of `constraint_setting()`'s and
`constraint_values()`'s that are specifically targetted towards embedded
development using Bazel. This differs from
[mainline platforms](https://github.com/bazelbuild/platforms) in that it
includes RTOS's, FPU's, DSP's and other extension sets specific to embedded
development. The intention with this repository is **NOT** to replace or extend
the [mainline platforms](https://github.com/bazelbuild/platforms).