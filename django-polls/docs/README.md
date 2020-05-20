# django-polls 安装

django-polls 以用户库的形式安装。与安装整个系统的软件包相比，用户安装具有许多优点，例如可在没有管理员访问权的系统上使用，以及防止应用包影响系统服务和其他用户。

1. 安装

```python
python -m pip install --user django-polls/dist/django-polls-0.1.tar.gz
```

2.幸运的话，你的 Django 项目应该再一次正确运行。启动服务器确认这一点。

3.通过 pip 卸载包:

```python
python -m pip uninstall django-polls
```
