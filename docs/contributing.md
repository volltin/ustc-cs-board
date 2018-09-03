## 内容维护

在 GitHub 上 fork 本仓库，在线编辑 docs 目录中的相应文件（比如计算机网络张老师班作业：docs/net/zhang/hw.md），最后提交 pull request 即可。也可以从 clone 到本地，本地编辑完成后提交 pull request。

如果觉得麻烦，可以联系维护者添加仓库的写权限，直接编辑文件。

## 技术细节

本网站源码和页面都位于 GitHub，使用 GitHub Pages 提供静态的网站。

源码提交到 GitHub 之后会自动触发 Travis CI 集成，先通过 mkdocs 编译，然后 push 到 gh-pages 目录，几分钟之内网站就会显示最新的内容。