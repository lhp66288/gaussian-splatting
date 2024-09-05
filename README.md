最近在学习使用3D Gaussian-splatting还原场景并在Unity中实现可视化，在这里记录一下遇到的一些问题和解决办法。

一.Gaussian-splatting项目下载
===
直接去Gaussian-splatting的github官网下载
官网链接：https://github.com/graphdeco-inria/gaussian-splatting

！！！直接下载压缩包或者使用git clone都会出现项目拉取不完整的问题，submodules文件夹很有可能下载不下来

解决办法：使用git clone --recursive https://github.com/graphdeco-inria/gaussian-splatting.git命令来拉去项目

