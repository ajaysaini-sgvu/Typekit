Typekit is an android library to make it easy, to use custom fonts.

<p align="left">
  &nbsp;<img src="https://github.com/ajaysaini-sgvu/Typekit/blob/master/device-2017-03-26-002705.png" width="350"/>
</p>

## Getting started

### Installation

Add gradle dependency with command:

```groovy
dependencies {
    compile 'com.nagarro.typekit:android-typekit:1.0'
    ...
}
```

### Add Fonts

Add your custom fonts to `assets/fonts`. All font definitions are relative to this path.

Assuming that you are using Gradle you should create the assets directory under `src/main/` in your project directory if it does not already exist.
As it's popular to use multi-project build with Gradle the path is usually `app/src/main/assets/fonts/`, where `app` is the project name.

### Usage

```xml

<com.nagarro.typekit.TextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:fontFamily="Roboto-Thin"
    android:text="Hello World"
    android:textSize="40sp"/>
``` 

### Version: 1.0.0

Stable release

## Licence

    Copyright 2017 Ajay Saini (TGMCians)
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
