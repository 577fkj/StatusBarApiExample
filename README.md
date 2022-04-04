# StatusBarAPi

![](https://www.jitpack.io/v/577fkj/StatusBarApiExample.svg)

[APIDemo](https://github.com/577fkj/StatusBarApiExample)

[Jitpack](https://www.jitpack.io/#577fkj/StatusBarApiExample/v2.0)

You need to add in build.gradle
```
allprojects {
    repositories {
        ....
        maven { url 'https://www.jitpack.io' }
    }
}


dependencies {
    implementation 'com.github.577fkj:StatusBarApiExample:v2.0'
}
```

```java
import StatusBarLyric.API.StatusBarLyric;
```

Attention: if proguard is enabled, make sure API class won't be obfuscated:
```shrinker_config
-keep class StatusBarLyric.API.StatusBarLyric {*;}
```


# StatusBarAPi

![](https://www.jitpack.io/v/577fkj/StatusBarApiExample.svg)

[APIDemo](https://github.com/577fkj/StatusBarApiExample)

[Jitpack](https://www.jitpack.io/#577fkj/StatusBarApiExample/v2.0)

需要在 build.gradle 添加
```
allprojects {
    repositories {
        ....
        maven { url 'https://www.jitpack.io' }
    }
}


dependencies {
    implementation 'com.github.577fkj:StatusBarApiExample:v2.0'
}
```

```java
import StatusBarLyric.API.StatusBarLyric;
```

注意: 若开启了 proguard 请保证 API 类不被混淆:
```shrinker_config
-keep class StatusBarLyric.API.StatusBarLyric {*;}
```
