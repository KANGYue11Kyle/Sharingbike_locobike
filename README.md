# Sharingbike_locobike

香港 Locobike 共享单车 FastAPI 接口项目。

## 📖 项目简介

基于 [FastAPI](https://fastapi.tiangolo.com/) 搭建的轻量 REST 接口服务，提供香港地区 Locobike 单车**点位查询**与**实时可用车辆数获取**功能，并支持自动生成交互式接口文档（Swagger UI）。

## ✨ 功能特性

- 🚲 查询香港地区 Locobike 单车点位
- 📊 获取实时可用车辆数
- 📄 自动生成交互式接口文档（`/docs`）
- ⚡ 基于 FastAPI，轻量、高性能、易扩展

## 🚀 快速启动

### 1. 安装依赖

```bash
pip install -r requirements.txt
```

### 2. 启动服务

```bash
uvicorn main:app --reload
```

### 3. 调试接口

打开浏览器访问：

```
http://127.0.0.1:8000/docs
```

即可在线调试所有接口。

## 📁 仓库说明

| 项目 | 说明 |
| --- | --- |
| 虚拟环境 | 已排除本地虚拟环境的 `Scripts`、`include` 目录，避免冗余文件占用仓库体积 |
| `requirements.txt` | 记录项目所有第三方依赖，保证跨环境复现一致 |
| 根目录 | 核心 API 逻辑与配置文件保留在根目录，结构清晰易修改 |

## 🛠 技术栈

- **框架**：FastAPI
- **服务**：Uvicorn
- **文档**：Swagger UI（自动生成）


## 🙏 致谢

locobike
