# Sharingbike_locobike

A FastAPI-based interface project for Locobike shared bicycles in Hong Kong.

## 📖 Project Overview

A lightweight REST API service built on [FastAPI](https://fastapi.tiangolo.com/), providing **station location queries** and **real-time available vehicle count retrieval** for Locobike bicycles in Hong Kong, with support for automatically generated interactive API documentation (Swagger UI).

## ✨ Features

- 🚲 Query Locobike bicycle station locations in Hong Kong
- 📊 Retrieve real-time available vehicle counts
- 📄 Automatically generated interactive API documentation (`/docs`)
- ⚡ Built on FastAPI: lightweight, high-performance, and easy to extend

## 🚀 Quick Start

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Start the Service

```bash
uvicorn main:app --reload
```

### 3. Debug the API

Open your browser and visit:

```
http://127.0.0.1:8000/docs
```

You can then debug all endpoints online.

## 📁 Repository Description

| Item | Description |
| --- | --- |
| Virtual environment | The `Scripts` and `include` directories of the local virtual environment have been excluded to avoid redundant files consuming repository space |
| `requirements.txt` | Records all third-party dependencies of the project to ensure consistent reproducibility across environments |
| Root directory | Core API logic and configuration files are kept in the root directory, making the structure clear and easy to modify |

## 🛠 Tech Stack

- **Framework**: FastAPI
- **Server**: Uvicorn
- **Documentation**: Swagger UI (auto-generated)


## 🙏 Acknowledgements

locobike
