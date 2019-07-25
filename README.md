# plugin-ifly-ext-android

Plugin of iFly IMKit extension. 科大讯飞语音输入插件,通过这个插件可以实现语音转文字的功能,如下图所示：

![](./images/image1.jpg)

如上图所示 “语音输入” 模块

![](./images/image2.jpg)

如上图所示，将你输入的语音转成文字显示在输入框

Android Studio 导入 recognizer moudle 

配置：

在 settings.gradle 中添加 'recognizer' 模块，如：

``` java
include ':recognizer'
```

在应用的 build.gradle 中添加依赖, 如：

``` java
api project(':recognizer')
```



