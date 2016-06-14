AndroidApp
===
Android library that features `onUpgrade` method for `Application` class.

Installation
---
This library requires at minimum Android 2.3.

**Maven**
```xml
<dependency>
  <groupId>net.coder966.AndroidApp</groupId>
  <artifactId>library</artifactId>
  <version>1.0.0</version>
  <type>pom</type>
</dependency>
```

**Gradle**
```gradle
compile 'net.coder966.AndroidApp:library:1.0.0'
```

Usage
---
Instead of inheriting `Application` class, inherit `AndroidApp` and you are done!

The method `onUpgrade` will be called only if the application has been updated, and it has 2 arguments, the old version code and the new one.

License
---
```
Copyright 2016 Khalid Alharisi

    Licensed under the GNU General Public License v3.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       https://www.gnu.org/licenses/gpl-3.0.txt

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
```
