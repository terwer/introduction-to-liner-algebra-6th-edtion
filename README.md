# 《线性代数导论》第六版中文版

欢迎阅读《线性代数导论》第六版中文版，本书由 terwer 翻译。

## 初始化

```
## 初始化 virtualenv
python3 -m pip install --user --upgrade pip
python3 -m pip --version

python3 -m pip install --user virtualenv
python3 -m venv venv

## 或者
curl https://pyenv.run | bash
# 然后设置换变量 https://github.com/pyenv/pyenv#set-up-your-shell-environment-for-pyenv
pyenv install 3.11.4
pyenv global 3.11.4
python -V
python -m pip install --user virtualenv
python -m venv venv

source venv/bin/activate
deactivate

## 安装依赖
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple sphinx
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple myst-parser
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple sphinx_rtd_theme
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple sphinx-rtd-size

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple -r requirements.txt
pip freeze > requirements.txt
```

## 项目构建

```
rm -rf build && make html
```

## 参考

https://blog.terwer.space/s/20230725134910-epk1oj8