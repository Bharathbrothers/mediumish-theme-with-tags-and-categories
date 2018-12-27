---
layout: post
title:  "How to develop a mobile Application"
author: sal
categories: [ Useful, tutorial, Android ]
tags: [coding, Android]
image: https://developer.android.com/studio/images/studio-homepage-hero.jpg
---
<style>
  @media  screen and (min-width : 0px) and (max-width : 767px)  {
  video{
      width: 200px;   
    height:300px;
    }
}
</style>
### Android Studio

This is the software required by you to develop an application for Android Devices. 
Android takes more than 85% of the entire mobile market in the world. So many developers are needed for this huge market. 
We can also develop applcations for Android along with Apps for IOS using latest Technologies like _React Native_ and _Flutter_
which helps you to take the entire market. You can read more about those technologies by scrolling down.

>Installing Android Studio with all the required packages and tools is the half-way done in the process of building apps using this software.
This is because its a heavy software which has many tools and takes a lot of space and memory on your computer.

**The minimum RAM required to run this software is 4GB and 8GB is the Ideal one along with a Good Processor with more clock speed.**

If you are a beginner and your Laptop doesn't support you, I suggest you to go with React Native which doesn't require these heavy softwares and has many great features while developing apps when compared with Android Studio. The one feature which I like most in React is that it has live-Reloading(_Changes are appeared as you keep on modifying them_) which is very handy whereas in Android Studio you have to build your app for every small change made to check whether its working or not.

Download Android Studio from this [link](https://developer.android.com/studio/).After successful Installation of this software start a new project and Create a **Emulator (Virtual Device)** to run your application on a virtual device which runs on your PC but takes out more Memory to run. After this you can check out the following links to learn Android or you can check out courses on [Udemy](https://udemy.com) (If you want an Organized way to learn Android) or you can check out **free tutorials** on [youtube](https://www.youtube.com/). You can download many paid **Udemy Courses** for free on this [website](https://www.freetutorials.eu/) if don't want to pay any rupee for any course. 

<hr>
### Android Basics Tutorials and links

Android App Samples [here](https://developer.android.com/samples/).

Codelabs tutorials are available [here](https://codelabs.developers.google.com/?cat=Android).

You can refer this post for more [info](https://starksources.github.io/myblog/useful/android/2018/11/15/Android.html)

Goal-Kicker Android tutorial pdf [link](https://books.goalkicker.com/AndroidBook/)

Google developers training [link](https://developers.google.com/training/courses/android-fundamentals)

Android Concepts by Google:[link](https://google-developer-training.github.io/android-developer-fundamentals-course-concepts/en/index.html).

Android Practicals by Google [link](https://google-developer-training.github.io/android-developer-fundamentals-course-practicals/en/index.html)

Android Fundamentals official youtube [playlist](https://www.youtube.com/playlist?list=PLlyCyjh2pUe9wv-hU4my-Nen_SvXIzxGB).

<hr>
#### Emulator

This is the virtual device on which you run your mobile applications. You can also run your apps directly on your mobile too.Here is a short video describing what are the things that you can do on Emulator.
<video center controls poster="/studio/images/run/thumbnail-emulator_2x.png" style="width:300px;height:400px;">
  <source src="https://storage.googleapis.com/androiddevelopers/videos/studio-emulator-overview_2-2.mp4" type="video/mp4">
</video>

<hr>
##### React Native

![React Native](https://kaysharbor.com/wp-content/uploads/2018/05/all-about-react-native-apps-776x415.png)

This is from facebook.

React Native helps you to build native-mobile applications using JavaScript(not like web-apps using HTML5) both for Android and IOS platform at one go.This helps to reach a larger Audience.

{% highlight react linenos %}
import React, { Component } from 'react';
import { Text, View } from 'react-native';

export default class HelloWorldApp extends Component {
  render() {
    return (
      <View>
        <Text>Hello world!</Text>
      </View>
    );
  }
}
{% endhighlight %}

This is the code for Hello World Application in React which is very easy when compared to java and xml code in Android Studio.

[Official Docs and tutorials for learning React Native](http://facebook.github.io/react-native/)

[React.js](https://reactjs.org/)

> I Suggest you to learn React Native from the above official link as it is constantly being updated. You might get into trouble if you follow any tutorial because the code might not work now as the community is constantly adding new features(_The thing which happened with me while I am learning this and made me to quit from learning React Native_). 

<hr>
#### Flutter

![Flutter](https://i.ytimg.com/vi/fq4N0hgOWzU/maxresdefault.jpg)

link [here](https://flutter.io/)

Flutter is developed by Google. It helps you to develop apps faster. Flutter allows you to build beautiful native apps on iOS and Android from a single codebase. Learn Flutter from the above link.

<hr>
### Ionic

![Ionic](https://www.quape.com/wp-content/uploads/2017/07/ionic.jpg)

[Link here](https://ionicframework.com/)

Ionic lets web developers build, test, and deploy cross-platform hybrid mobile apps easier than ever. check out the above link to know more.

<hr>
### Andoid Assets Studio for Icons

![Assets Studio](https://i1.wp.com/www.snyxius.com/wp-content/uploads/2018/04/android-asset-studio.png?ssl=1)
[Link here](https://romannurik.github.io/AndroidAssetStudio/index.html)

This is useful for you to create Icons for your Apps.


> Thank you for reading this blog. Make sure to comment for any help.


