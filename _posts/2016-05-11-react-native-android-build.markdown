---
layout: post
title:  "react-native android build"
date:   2016-05-11 10:38:15
categories: javascript react-native app
---

### 权限不足
直接 react-native run-android 出现错误，然后换用 sudo react-native run-android 成功，估计是我自己安装的权限问题，按理应该不会出现这种问题。

#### gradle-2.4-all.zip 下载超级慢，有时候还直接报错
这个文件我直接下载很快，但是就在cli里面很慢，解决办法就是替换掉下载路径，我直接改到本地路径
{% highlight ruby %}
    ./android/gradle/wrapper/gradle-wrapper.properties
    #distributionUrl=https\://services.gradle.org/distributions/gradle-2.4-all.zip
    distributionUrl=http\://localhost/gradle-2.4-all.zip
{% endhighlight %} 




[kenlyau.github.io][link]

[link]:    https://kenlyau.github.io
