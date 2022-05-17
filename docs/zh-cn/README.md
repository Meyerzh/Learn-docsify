# 快速学习 `docsify` 文档 in zh-cn

> An awesome project.


## 快速开始
全局安装 `docsify-cli` 工具
```bash
npm i docsify-cli -g
```
npm 查看全局安装过的包命令
```bash
npm list -g --depth 0
```

## 初始化项目
```bash
docsify init ./docs
```

## 本地预览
通过运行 `docsify serve` 启动一个本地服务器，可以方便地实时预览效果。默认访问地址 http://localhost:3000 。
```bash
docsify serve docs
```

如果你的系统里安装了 Python 的话，也可以很容易地启动一个静态服务器去预览你的网站。
```python2
cd docs && python -m SimpleHTTPServer 3000
```
```python3
cd docs && python -m http.server 3000

python3 -m http.server 3000 # Mac
```

