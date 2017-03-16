## What is it?
Google's library for managing [APK expansion files](http://developer.android.com/google/play/expansion-files.html).

**Note:** This is *not* a direct copy of Google's library. It includes additional bug fixes and improvements. These include a workaround to an [Android 6 permissions bug](https://code.google.com/p/android/issues/detail?id=197287), which requires users to download two copies of your expansion file. As such, it may not be suitable for projects with very large expansion files.

## Why here?
Because of Google hasn't published it to any repository yet.

## Where published?
[Here](https://bintray.com/alexeydanilov/apk-expansion)

## How to use?
Modify `build.gradle`:
```
repositories {
    maven { url 'https://dl.bintray.com/alexeydanilov/apk-expansion' }
}

dependencies {
    compile 'com.danikula.expansion:expansion:VERSION@aar'
    compile 'com.danikula.expansion:license:VERSION@aar'
    compile 'com.danikula.expansion:zip:VERSION@aar'
}
```
See the latest versions [here](https://bintray.com/alexeydanilov/apk-expansion).

## Thanks
Thanks for [bintray-release](https://github.com/novoda/bintray-release) for easy publishing.

## Licence

    Copyright 2015 Alexey Danilov

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.LICENSE