# 设置pip包源加速包源下载

## 配置

    ```
    vim ~/.pip/pip.conf

     [global]
     trusted-host =  mirrors.aliyun.com
     index-url = http://mirrors.aliyun.com/pypi/simple
    ```

## pyenv 下载python速度较慢解决办法

1. 在`~/.pyenv/cache`目录下载所需版本的安装包
2. 继续执行 `pyenv install 所需版本号`

可用的国内包源有
[搜狐镜像](http://mirrors.sohu.com/python/)

##### 2018-03-09 Fri

