## Android Dialer
Android Dialer for Android N (derived from https://github.com/geniusgithub/AndroidDialer)

Go through https://codelabs.developers.google.com/codelabs/cosu/index.html

Customised Android Dilaer to use as single-use, only phone calls are allowed once set.

Useful for people who wants to use smartphone as a feature phone. example, my parents :)

Set as device owener with below command

adb shell dpm set-device-owner org.android.dialer/com.android.dialer.DeviceAdminReceiver

##LIB:
* com.android.support:appcompat
* com.android.support:appcompat:recycleview
* com.android.support:appcompat:cardview
* com.android.support:appcompat:design
* com.android.support:support-v13

##Run requirements
Android OS 5.0 and up

 
##License

     Copyright (C) 2016 The Android Open Source Project
     Licensed under the Apache License, Version 2.0 (the "License");
     you may not use this file except in compliance with the License.
     You may obtain a copy of the License at

          http://www.apache.org/licenses/LICENSE-2.0

     Unless required by applicable law or agreed to in writing, software
     distributed under the License is distributed on an "AS IS" BASIS,
     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
     See the License for the specific language governing permissions and
     limitations under the License.

