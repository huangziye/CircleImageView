
[![](https://jitpack.io/v/huangziye/CircleImageView.svg)](https://jitpack.io/#huangziye/CircleImageView)

# Add ` CircleImageView ` to project

- Step 1：Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

```android
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

- Step 2：Add the dependency

The latest version shall prevail.

```android
dependencies {
        implementation 'com.github.huangziye:CircleImageView:${latest_version}'
}
```




# Effect picture


![圆形图片效果图](https://github.com/huangziye/CircleImageView/blob/master/screenshot/CircleImageView.png)


# Usage

```xml
<com.hzy.circle.CircleImageView
        android:layout_width="100dp"
        android:layout_height="100dp"
        android:src="@mipmap/a"
        android:layout_marginTop="10dp"
        app:civ_border_width="2dp"
        app:civ_border_color="@color/colorAccent"/>
```



### [reference](https://github.com/hdodenhof/CircleImageView)



# About me


- [简书](https://user-gold-cdn.xitu.io/2018/7/26/164d5709442f7342)

- [掘金](https://juejin.im/user/5ad93382518825671547306b)

- [Github](https://github.com/huangziye)


# License

```
Copyright 2018, huangziye

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```



