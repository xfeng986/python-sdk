# python-sdk
# 打包方法
## 打包方法一：
1. python setup.py bdist_egg    
2. 之后将整个目录打包发给调用方
## 打包方法二：
1. python setup.py bdist_wheel
2. 之后将dist目录下的wheel文件发给调用方
    
# 安装和使用SDK
## 安装和使用SDK一：
1. 解压，进入主目录下
2. python setup.py install 安装
3. import demo 在python程序中，调用安装好的demo包, demo.hell()
## 安装和使用SDK二：
1. pip install xxx.whl --user
2. import demo 在python程序中，调用安装好的demo包, demo.hell()

## Reference
1. https://packaging.python.org/tutorials/packaging-projects/
2. https://github.com/xfeng986/python-sdk.git
