# DanTinyHttpd
TinyHttpd官方源码请在此链接获取：[https://sourceforge.net/projects/tinyhttpd/?source=typ_redirect](https://sourceforge.net/projects/tinyhttpd/?source=typ_redirect)  

本项目是对TinyHttpd的注释学习，并针对Ubuntu16.04下的运行进行了文件修改，已经过本地测试。  

文件说明：
httpd.c-----对官方文件进行修改，在Ubuntu下使用多线程运行，无注释。  
httpd-with-comment.c-----对多线程版进行了注释。  
httpd-without-pthread.c-----按照原版注释修改的阻塞版本，注释由他人标注，仅仅引用供参考。  
  
使用说明：

```bash
git clone https://github.com/Supredan/DanTinyHttpd
cd DanTinyHttpd
make
./httpd
```

详见我的博客：
