# CLIProxyAPI 一键部署脚本

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Docker](https://img.shields.io/badge/Docker-Supported-blue)](https://www.docker.com/)
[![Linux](https://img.shields.io/badge/OS-Debian%20%7C%20Ubuntu%20%7C%20CentOS-success)]()

这是一个用于快速部署 [CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) 的 Shell 脚本。它集成了环境检测、Docker 自动安装、密钥配置以及服务管理功能，旨在让你在 Linux 服务器上通过一行命令完成部署。

## ✨ 功能特性

- 🐧 **全系统支持**：支持 Debian, Ubuntu, CentOS, AlmaLinux, Rocky Linux 等主流发行版。
- 🐳 **自动环境配置**：自动检测并安装 Docker 和 Docker Compose，无需手动配置。
- 🔑 **交互式配置**：安装过程中可自定义管理面板密钥 (Secret Key)。
- 🔄 **完整生命周期管理**：支持一键安装、更新、卸载、查看日志和重启服务。
- 📂 **标准化目录**：所有配置文件和数据存储在 `/home/docker/cliproxyapi`，易于备份。

## 🚀 快速开始

使用 Root 用户在终端执行以下命令即可启动脚本菜单：

```bash
bash <(curl -sL https://raw.githubusercontent.com/NX2406/cli/main/install)
