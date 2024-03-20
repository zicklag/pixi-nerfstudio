# Pixi Nerfstudio Env

A simple pixi environment for installing
[nerfstudio](https://docs.nerf.studio/quickstart/installation.html).

## Usage

Until [this PR](https://github.com/prefix-dev/pixi/pull/985) is merged, we need to run a
`pixi install`, followed by a `pip install -r requirements.txt`.

It'd be nice to make a proper conda package for nerfstudio so that you don't have to wait
for tiny_cuda_nn to avoid having to wait for it to build locally when we run the pip install.

