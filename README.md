# SlantedTextView  倾斜TextView
Android slanted TextView . [中文版](https://github.com/HeZaiJin/SlantedTextView/blob/master/README-cn.md)
## Preview
![预览](https://github.com/HeZaiJin/SlantedTextView/blob/master/screen_shot/screenshot.png)
## Gradle
```java
compile 'com.haozhang.libary:android-slanted-textview:1.0'
```
## XML Layout
```java
<com.haozhang.lib.SlantedTextView
    android:layout_width="80dp"
    android:layout_height="80dp"
    android:gravity="center"
    app:slantedBackgroundColor="@color/secondary_text"
    app:slantedLength="40dp"
    app:slantedMode="left"
    app:slantedText="IOS"
    app:slantedTextColor="@color/primary"
    app:slantedTextSize="16sp"
    />
```
## Java
```java
    SlantedTextView stv = (SlantedTextView) findViewById(R.id.test);

    stv.setText("PHP")
            .setTextColor(Color.WHITE)
            .setSlantedBackgroundColor(Color.BLACK)
            .setTextSize(18)
            .setSlantedLength(50)
            .setMode(SlantedTextView.MODE_LEFT);
```
## Notice
![注意](https://github.com/HeZaiJin/SlantedTextView/blob/master/screen_shot/note.png)
#License
```
Copyright 2016 Hand HaoZhang

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
