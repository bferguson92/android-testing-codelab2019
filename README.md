# Android Testing Codelab

This folder contains the source code for the Android testing codelab. It gives an introduction into testing on Android, including unit tests and UI tests.
https://codelabs.developers.google.com/codelabs/android-testing/

what testing framework you used and why?

Some of the testing frameworks used were Robolectric which allows the running of  instrumentation test on the JVM instead of a real or virtual device. The androidx test libraries which try to connect local testing and instrumentation testing, which includes the JUnit as the test runner. Also there is Espress  testing framework for integration test.

What type of tests were performed(unit, functional or Ui)?

There is the Unit test which are test on run on a single class or method and when it fails you should know know where it failed from the test, it is run on the JVM and does not need to use a device or emulator. There also Integration testing which test several classes and the interaction between them and this does need a device or emulator to run. Last there are End-to-End test which test large portions of the app by testing combinations of features you implemented they are longer and also require a emulator or device.

### License


```
Copyright 2019 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements. See the NOTICE file distributed with this work for
additional information regarding copyright ownership. The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License. You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations under
the License.
```
