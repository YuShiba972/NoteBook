# <center>Yushiba972的个人笔记项目配置说明<center>

------------------------------------------------------------------------


1. build/：sphinx项目构建后生成的html文件存放文件夹。
1. source/：sphinx项目的源文件夹，包括模板文件、静态文件。
1. make.bat：Windows系统的sphinx项目构建脚本，提供sphinx项目构建命令，简化构建过程。
1. Makefile：Unix系统(Linux、MacOS)的sphinx项目构建脚本，提供sphinx项目构建命令，简化构建过程。
1. requirements.txt：项目依赖的环境列表，此处提供在read the docs上部署使用。
1. .readthedocs.yaml：项目部署在read the docs上所需要的配置文件，控制自动化构建的过程。
1. .gitignore：git版本控制中忽略的文件，此处忽略build中的临时文件。