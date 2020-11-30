# Change Log
autoxjs 整个项目的的一些更新日志。

### 4.2.10
优化以下特性：
* 稳定支持 websocket


### 4.2.9
优化以下特性：
* 感谢 Wang Zijian 修复 floating window permission check on miui
* console的自动隐藏改为参数控制
* 打包apk启动后finish掉启动也
* 升级apkbuild包,解决空文件夹问
* 升级ci 项目

### 4.2.8
优化以下特性：
* 调整模板app，添加常驻前台，现在是统一自动开启
* 修复打包插件，无法识别空目录，导致无法重新打包识别
* 统一模板app和autoxjs，不再采用插件形式打包
* 修复了4.2.7 的遗留问题


### 4.2.7
优化以下特性：
* 添加获取设备虚拟导航栏相关接口：是否有虚拟导航，虚拟导航高度
* 去除打包插件机制，直接使用模板打包
* 修复release发布，不能运行bug
* 修复release模式下语言包找不到问题
`注意`遗留一个问题这里面的模板不是最新,最新升级的接口，打包出来无法使用,在autoxjs中可以正常使用


### 4.2.6
优化以下特性：
* 修复console 界面未创建，修改过程产生空指针问题
* 默认可以不修改console 原标题
* 关闭console的提示，修改为系统消息
  


### 4.2.5
优化以下特性：
* 添加应用商店需要的功能（商店端暂未上线）
* 日志：标题字号，色彩，背景，文字大小，内容字号等可以设置和修改
* 和vscode 插件链接问题闪退问题
* TextView 导致小米手机闪退问题
* 
