# cocos2d-jsGAME
游戏梦想起航－－基于JS的游戏开发！
###初步认识：
首先：cocos是一款过人开发的2d游戏引擎，可以支持很多种语言的程序编写，比如说C++/lua/js等  
我所学习的是基于JS编写的程序。可以支持web／ios／android三个平台。可以说是一举三得，  
####开发工具：[基本教程](http://www.cocos.com/docs/creator/getting-started/dashboard.html)
  目前主流推荐的是Cocos Creator这个IED，他的好处就是将一个游戏的开发全部过程全部集中在一个IDE里面  
包括：设计、开发、预览、调试到发布等等  
除此之外，这个IDE还支持’设计化‘开发，不需要写代码即可开发！  
#####注意点：
1. 打开IDE需要输入cocos的开发者帐号，我的邮箱是961113052@qq.com 然后会出现dashboard（仪表盘）来管理所开发的各个项目
2. [资源导入——图片／音频等](http://www.cocos.com/docs/creator/asset-workflow/index.html)  

####一个游戏的基本组成部分：
1. 场景  
2. 图片资源／音频资源／字体（系统字体，动态字体和位图字体）等等  
3. 代码  

##基本开发步骤： 
1. 导入所需要的资源文件  
2. 创建场景：(canvas) 一个场景中一般包括：  
   场景图像和文字（Sprite，Label）  
   角色  
   以组件形式附加在场景节点上的游戏逻辑脚本  
   等等！  
   然后将资源文件以节点的方式拖拽到canvas里，并且设置其相关属性  
3. js脚本的名称对大小写诗敏感的    
   代码表示组件，资源表示节点，组件是挂在节点上的，给予节点动作，  
   同时，当我们创建一个js代码（组件）的时候，里面的初始化代码所表示此为一个cocos的组件！

