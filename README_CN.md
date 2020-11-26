# ProjectTemplate-Python

[English](README.md) **|** [简体中文](README_CN.md) &emsp; [GitHub](https://github.com/xinntao/ProjectTemplate-Python) **|** [Gitee码云](https://gitee.com/xinntao/ProjectTemplate-Python)

## 文件修改

1. 设置 *pre-commit* hook.
    1. 若需要, 修改 `.pre-commit-config.yaml`
    1. 在文件夹根目录, 运行
    > pre-commit install
1. 修改 `.gitignore` 文件
1. 修改 `LICENSE` 文件
    本仓库使用 *MIT* 许可, 根据需要可以修改成其他许可
1. 修改 *setup* 文件
    1. `setup.cfg`
    1. `setup.py`, 特别是其中包含的关键字 `basicsr`
1. 修改 `requirements.txt` 文件
1. 修改 `VERSION` 文件

## GitHub Workflows

1. [pylint](./github/workflows/pylint.yml)
1. [gitee-repo-mirror](./github/workflow/gitee-repo-mirror.yml) - 支持 Gitee码云
    1. 在 [Gitee](https://gitee.com/) 网站克隆 Github 仓库
    1. 修改 [gitee-repo-mirror](./github/workflow/gitee-repo-mirror.yml) 文件
    1. 在 Github 中的 *Settings* -> *Secrets* 的 `SSH_PRIVATE_KEY`

## 其他流程

1. 主页上的 `description`, `website`, `topics`
1. 支持中文文档, 比如, `README_CN.md`
