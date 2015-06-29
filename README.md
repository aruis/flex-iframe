![flex-iframe](https://github.com/flex-users/flex-iframe/raw/master/library/src/com/google/code/flexiframe/assets/flex-iframe-logo-128.png) [![Build Status](https://buildhive.cloudbees.com/job/flex-users/job/flex-iframe/badge/icon)](https://buildhive.cloudbees.com/job/flex-users/job/flex-iframe/)

***IFrame component for Flex applications** (project formerly hosted at [Google code](http://code.google.com/p/flex-iframe)).*

**All the documentation is [available on the wiki](https://github.com/flex-users/flex-iframe/wiki).**

#####一些改进：修正了iframe页面被flex弹窗遮挡的问题，主要参考http://blog.csdn.net/yj451928923/article/details/9104577
#####如果想避免遮挡问题，flex端代码还得调整，就是把包裹iframe容器的所有递归容器的背景透明度设置为0
```
  //例如
  <s:Application xmlns:fx="http://ns.adobe.com/mxml/2009" xmlns:s="library://ns.adobe.com/flex/spark"
               xmlns:iframe="com.google.code.flexiframe.*" xmlns:mx="library://ns.adobe.com/flex/mx" backgroundAlpha="0"
        >
        <!-- ... -->
  </s:Application>      
```
