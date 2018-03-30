前提：sass是基于ruby开发出来的，所以得先安装ruby；

1.安装sass的方法：
    方法一：
    通过命令安装sass：
        window版本：gem install sall
        mac版：     sudo gem install sass
    方法二：通过compass框架来安装sass；
    
    方法三：
        本地安装：
            1）.下载安装包：官网(http://rubygems.org）
            2）.命令行输入：gem install path(安装包路径),回车等待安装完毕；
            
2.由于网络受限原因，无法安装时处理方法：
    1).更换源:
            第一步：移动默认的源
            
            gem sources --remove https://rubygems.org/
            
            第二步：指定淘宝的源
            
            gem sources -a https://ruby.taobao.org/
            
            第三步：查看指定的源是不是淘宝源
            
            gem sources -l
            
            返回结果如下：
            
            *** CURRENT SOURCES ***
            https://ruby.taobao.org
            
            请确保只有 ruby.taobao.org。如果无误之后，执行下面的命令：
            
            gem install sass
