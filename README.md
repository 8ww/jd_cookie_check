## jd_cookie_check

步骤一：创建虚拟环境并进入

```
python -m venv venv
.\venv\Scripts\activate
```

步骤二:安装环境

```
pip install -r requirements.txt
```

步骤三：添加Cookie

```
# 假设你的Cookie信息放在本地 cookies.txt，每行一个Cookie，格式如：pt_key=xxx;pt_pin=yyy;
# 你也可以直接在代码中写明Cookies列表。
```

步骤四：运行检测

```
python cookie_check.py
```

