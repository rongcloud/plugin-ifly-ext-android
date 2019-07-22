# demo-ifly-ext-android

Demo of iFly IMKit extension. 科大讯飞语音输入插件示例。

Android Studio 导入 recognizer moudle 

配置：

在 settings.gradle 中添加 'recognizer' 模块，如：

include ':recognizer'

在应用的 build.gradle 中添加依赖, 如：

api project(':recognizer')

