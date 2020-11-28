# python-sdk, based on https://github.com/snowroll/python-sdk.git
打包方法：
1. python setup.py bdist_egg    
2. 之后将整个目录打包发给调用方
or
1. python setup.py bdist_wheel
2. 之后将dist目录下的wheel文件发给调用方
    
安装和使用SDK：
1. 解压，进入主目录下
2. python setup.py install 安装
3. import demo 在python程序中，调用安装好的demo包, demo.hell()
or
1. pip install xxx.whl --user
2. import demo 在python程序中，调用安装好的demo包, demo.hell()
