# 说明
uniapp 项目 Android离线打包基座。

- 基于HBuilder-Integrate-AS空项目（仅一个首页，运行后可以看到，如果是空白页，则表示异常，需要自己检查环境配置）
- 支持生成android_debug.apk后在HBuilderX里调试。

# 环境
- Gradle 版本 8.11.1
- AGP(Android Gradle Plugin) 版本 8.7.3)
- CompileSdk 35
- targetSdkVersion 35
- minSdkVersion 21
- local.properties修改为自己电脑SDK目录
- 搜索"replace-with-"查找所有要替换的内容

更多问题请参考[官方文档](https://nativesupport.dcloud.net.cn/AppDocs/usesdk/android.html)