# typst-buildpack

A tiny buildpack that download the `typst` CLI binary onto an image using a
Cloud Native Builpack

The `typst` utility will be available during *build* and *launch*

## Usage

Add the following lines to your `project.toml` file:

``` toml
[[io.buildpacks.group]]
  uri = "ghcr.io/flagcatstudio/buildpacks/flagcatstudio_typst-buildpack:0.1.0"
```
