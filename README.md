# Introduction

Gnucash Android is companion application for desktop Gnucash designed for Android.
It allows you to record transactions on-the-go and export them in the QIF, OFX or (GnuCash)-XML format and later import the data into Gnucash for the desktop. The app supports multiple nested accounts, scheduled transactions and backup/export to 3rd-party services (like DropBox & Google Drive).

The application supports Android 2.3.4 Froyo (API level 10) and above. 


# Installation

There are different ways to get the Gnucash app for Android; through the app store, or building it yourself.


### App Store

<a href="http://play.google.com/store/apps/details?id=org.gnucash.android">
  <img alt="Android app on Google Play" src="http://developer.android.com/images/brand/en_generic_rgb_wo_60.png" />
</a>


## Building

### With Gradle

This project requires the [Android SDK](http://developer.android.com/sdk/index.html)
to be installed in your development environment. In addition you'll need to set
the `ANDROID_HOME` environment variable to the location of your SDK. For example:

    export ANDROID_HOME=/home/<user>/tools/android-sdk

After satisfying those requirements, the build is pretty simple:

* Run `gradlew build installDevelopmentDebug` from the within the project folder.
It will build the project for you and install it to the connected Android device or running emulator.

The app is configured to allow you to install a development and production version in parallel on your device.

### With Android Studio
The easiest way to build is to install [Android Studio](https://developer.android.com/sdk/index.html) v1.+
with [Gradle](https://www.gradle.org/) v2.2.1.
Once installed, then you can import the project into Android Studio:

1. Open `File`
2. Import Project
3. Select `build.gradle` under the project directory
4. Click `OK`

Then, Gradle will do everything for you.

## Contributing

There are several ways you could contribute to the development.

One way is providing translations for locales which are not yet available, or improving translations.
See this [blog post](http://www.codinguser.com/2012/09/gnucash-for-android-beta-2-lost-in-translation/) for some guidelines.

You could as well contribute code, fixing bugs, new features or automated tests.
Take a look at the [bug tracker](https://github.com/codinguser/gnucash-android/issues?state=open)
for ideas where to start.

For development, it is recommended to use the Android Studio for development which is available for free.
Import the project into the IDE using the build.gradle file. The IDE will resolve dependencies automatically.

#Licence
Gnucash for Android is free software; you can redistribute it and/or 
modify it under the terms of the Apache license, version 2.0.
You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and 
limitations under the License.
