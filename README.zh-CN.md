# Build Vendor

[![License](https://img.shields.io/github/license/zhanglianxin/build-vendor)](LICENSE)

这是一个练手项目，学习使用 GitHub Actions 编排 CI/CD 工作流。

用于在 GitHub Actions 上构建 PHP 和 Node.js 项目依赖的工作流，完美解决小鸡 VPS 的资源限制问题！

小鸡玩家狂喜 😁😁 ！！

## 功能

### PHP 项目

[![Build vendor of PHP project](https://github.com/zhanglianxin/build-vendor/actions/workflows/online-repo.yml/badge.svg)](https://github.com/zhanglianxin/build-vendor/actions/workflows/online-repo.yml)

- 使用 GitHub Actions 构建 `vendor` 目录
- 帮你执行 `composer install`，避免各种问题 
- 支持 PHP 不同版本（前提是依赖定义文件 `composer.json` 中支持）
- 开发/生产依赖分离

### Node.js 项目

[![Build pages of httpstatuses.io](https://github.com/zhanglianxin/build-vendor/actions/workflows/httpstatuses.yml/badge.svg)](https://github.com/zhanglianxin/build-vendor/actions/workflows/httpstatuses.yml)

- 使用 GitHub Actions 构建静态资产
- 不用本地执行 `npm build`，无需环境
- 支持 Node.js 不同版本
> [!WARNING]
> 需要一些修改，请自便 🙃

## 为什么有/用此项目？

~~不是我们用不起而是~~小鸡 🐤 更有性价比。

无需搭建环境，无痛安装依赖和构建生产依赖或发布产物，节省服务器资源。

## 使用方法

1. 跳转到 Actions 标签页
2. 选择你的工作流
3. 点击运行工作流
4. 如果需要，输入参数
5. 开始运行工作流
6. 等待工作流运行结束，下载构建产物

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。
