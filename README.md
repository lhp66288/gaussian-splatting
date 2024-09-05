最近在学习使用3D Gaussian-splatting还原场景并在Unity中实现可视化，在这里记录一下遇到的一些问题和解决办法。

一.Gaussian-splatting项目下载
===
直接去Gaussian-splatting的github官网下载
官网链接：https://github.com/graphdeco-inria/gaussian-splatting

！！！直接下载压缩包或者使用git clone都会出现项目拉取不完整的问题，submodules文件夹很有可能下载不下来

解决办法：使用git clone --recursive https://github.com/graphdeco-inria/gaussian-splatting.git 命令来拉取项目

二.环境搭建
===
！！！版本问题是我进行训练的一个巨坑，我项目学习时间为2024.9.4
1.我使用的Python版本为3.12.5
2.Visual studio版本为最新的2022.17.11.2，由于VS版本和CUDA版本不一致我吃了很多苦头。
3.CUDA版本要使用！！！12.4版本以上，因为VS版本更新太快（旧版本安装起来不是很方便），版本较低的CUDA识别不了新版本的VS，这就会导致文件编译出现问题。

