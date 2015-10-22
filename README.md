###综合概述###

jQuery在1.7.x版本中，去掉了对浏览器嗅探支持，建议使用特性检测，然而在实际项目中，或多或少也需要这个功能

###兼容性###

IE6+、Chrome、Firefox、Safari、Opera

###框架依赖###

原生JS支持

###模块支持###

支持AMD、node和浏览器

###使用介绍###
1.识别引擎、举例如下：
    
    //如果浏览器是webkit核心，执行以下代码
    if(!!client.engine.webkit){
        //todo
    }
   
2.识别浏览器、举例如下：
        
      //如果是IE浏览器，且IE的版本是6，  执行以下代码
      if(!!client.browser.ie && client.browser.ie == 6){
          //todo
      }  
      
3.操作系统的识别、举例如下：
      
      //如果是win7系统，执行以下代码
      if(!!client.system.win && client.system.win == 7){
        //todo
      }
    
###下载连接###

https://github.com/hehongwei44/userAgent

###授权信息###

授权类型：MIT

授权类型信息：https://github.com/hehongwei44/userAgent/blob/master/LICENSE

###更改日志###

https://github.com/hehongwei44/userAgent/blob/master/ChangeLog.md

###其他补充###

一个很不错的的插件，值得推荐



