# Stardoc - Starlark Documentation Generator

[![Build status](hhttps://badge.buildkite.com/d8594eb71e4869c792cce22428b08e03b345f9c65dc603d70b.svg?branch=master)](https://buildkite.com/bazel/skydoc-postsubmit)

Stardoc is a documentation generator for [Bazel](https://bazel.build) build rules
written in [Starlark](https://bazel.build/docs/skylark/index.html).

Stardoc provides a Starlark rule (`stardoc`) that can be used to build documentation
for Starlark rules in Markdown. Stardoc generates one documentation page per `.bzl` file.

## Get Started

* How to [set up Stardoc for your project](docs/getting_started_stardoc.md)
* Writing [docstrings](docs/writing_stardoc.md)
* How to [integrate Stardoc with your build](docs/generating_stardoc.md).

## About Stardoc

* How to [contribute to Stardoc](docs/contributing.md)
* See the [Stardoc roadmap](docs/roadmap.md)

## Skydoc deprecation

Stardoc is a replacement for the **deprecated** "Skydoc" documentation generator.

See [Skydoc Deprecation](docs/skydoc_deprecation.md) for
details on the deprecation and migration details.
