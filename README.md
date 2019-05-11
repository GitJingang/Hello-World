# Hello-World
gitHub初步使用新建一个仓库，看看效果如何
初步学习了创建分支，测试一下还是不错的。
mysql数据库安装地址：https://dev.mysql.com/downloads/file/?id=469270

# disruptor(观察者模式，或者事件监听模式)官方学习网站：
http://ifeve.com/disruptor-getting-started/
maven 创建：
<dependency>
   <groupId>com.lmax</groupId>
   <artifactId>disruptor</artifactId>
   <version>3.4.2</version>
</dependency>

# 如何将本地或者下载的jar包引入到maven项目中
https://blog.csdn.net/luoweiyou/article/details/79639588
 root]#  mvn install:install-file   -Dfile=java-bloomfilter-1.0.jar  -DgroupId=com.sina  -DartifactId=java-bloomfilter -Dversion=1.0  -Dpackaging=jar
           上面的命令解释：
            -Dfile：指明你当前jar包的位置（就是第1步存放jar的路径+jar包名）；
            -DgroupId， -DartifactId，  -Dversion：三个参数，就是指明了存放maven仓库中的位置；
            -Dpackaging ：猜测就是指明文件类型；
--------------------- 
