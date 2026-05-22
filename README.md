# SuSu-BookRead-DeepLearningModels
基于图像识别技术，为BookRead应用提供书籍信息分析的深度学习模型

## 项目说明


## 项目结构

## 项目依赖
1. 安装uv
```
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```
2. 安装ruff
```
# 先重启powershell
# 初始化uv项目（自动创建虚拟环境）
uv init --lib

# 安装ruff（代码检查工具）
uv add --dev ruff
```
3. 安装其他依赖
```
uv sync
Installed 25 packages in 1m 00s
 + cfgv==3.5.0
 ~ deeplearningmodels==0.1.0 (from file:///D:/DeepLearningModels)
 + distlib==0.4.0
 + filelock==3.29.0
 + fsspec==2026.4.0
 + identify==2.6.19
 + jinja2==3.1.6
 + markupsafe==3.0.3
 + mpmath==1.3.0
 + networkx==3.6.1
 + nodeenv==1.10.0
 + numpy==2.4.6
 + opencv-python==4.13.0.92
 + pillow==12.2.0
 + platformdirs==4.9.6
 + pre-commit==4.6.0
 + python-discovery==1.3.1
 + python-dotenv==1.2.2
 + pyyaml==6.0.3
 + setuptools==81.0.0
 + sympy==1.14.0
 + torch==2.12.0
 + torchvision==0.27.0
 + typing-extensions==4.15.0
 + virtualenv==21.3.3
```

## 使用说明

## 开发和调试

1. 代码格式检查
```
# 代码格式化
uv run ruff format src/

# 代码 lint 检查
uv run ruff check src/

# 自动修复可修复的问题
uv run ruff check src/ --fix
```