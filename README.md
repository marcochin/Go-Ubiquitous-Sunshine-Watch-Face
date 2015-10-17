Go-Ubiquitous-Sunshine-Watch-Face
===================================

Android Wear: A custom watch face for Android Wear that uses the Sunshine weather app to display the weather along with the time.

* This watch face uses the `Wearable.MessageApi` to send and receive messages to and from the `WearableListenerService`. 
* The `WearableListenerService` then queues the `ContentProvider` for today's forecast and sends it as a msg to the wearable. The forecast is finally drawn on the watch face along with the time!
* The app synchronizes weather information from OpenWeatherMap on Android Phones and Tablets. Used in the Udacity Advanced Android course.

Preview
---
<b>Interactive Mode (left) and Ambient mode (right)</b>
![](http://i.imgur.com/HKkqH79.png)

<img src="http://i.imgur.com/g8oX0UK.png" width="709" height="310">


Getting Started
---------------
This sample uses the Gradle build system.  To build this project, use the
"gradlew build" command or use "Import Project" in Android Studio.

License
-------
Copyright 2015 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.

