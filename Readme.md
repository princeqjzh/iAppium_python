**安卓自动化测试程序（Python版）**
运行环境：
- appium server
- python3
- pytest
- git

配置文件：iAppium_python.json
- 将配置文件复制到本地磁盘
- 填入设备的 deviceName 与 udid

运行命令：
pytest -v test/cm_test.py --tc-file /full_path/iAppium_python.json --tc-format json