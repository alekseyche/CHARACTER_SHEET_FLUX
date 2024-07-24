## 欢迎来到 Cloud Studio ##

当前模板包含最简单的Hello World以及运行指令的Python示例代码仓库

##  “运行”按钮怎么使用 ##

点击运行按钮会自动运行，是因为有 `.vscode/preview.yml` 文件存在。

该文件的格式说明如下：

```yml
# .vscode/preview.yml
autoOpen: false
apps:
  - port: 5000
    run: 'pip install -i https://mirrors.tencent.com/pypi/simple/ -r ./requirements.txt && python ./app.py'
    root: ./web
    name: Python Cloud Studio Demo
    description: Python Cloud Studio Demo Project
    autoOpen: true

```