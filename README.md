# Notice
This project is unmaintained, but feel free to fork it.

![](https://raw.githubusercontent.com/mrzapp/opengui/master/Images/logo.png)

### What?
It's a GUI framework for Unity that aims to keep things as simple as possible while keeping draw calls to an absolute minimum. I am developing this in tandem with my Deus Ex-based game project [The Vongott Chronicles](http://jeppezapp.com/vongott/)

### Why?
GI frameworks for Unity are overpriced, and the built-in API is a ridiculous resource hog with every widget requiring one or more draw calls each. And we can't expect Unity to provide a decent UI system "sometime in the future", when we are ready to develop games now :) So this framework is using the OpenGL API to render widgets, and trying its best to be simple and easy to use at the same time.

### Demo
[![demo](https://raw.githubusercontent.com/mrzapp/opengui/master/Images/webdemo.jpg)](http://htmlpreview.github.io/?http://github.com/mrzapp/opengui/blob/master/Build/Build.html)

### Documentation and tutorials
In the [wiki](https://github.com/mrzapp/opengui/wiki)

### FAQ
#### I have created widgets, but nothing is displaying. What might be wrong?
Make sure your [`OGPage`](https://github.com/mrzapp/opengui/wiki/OGPage) object is the current one, and make sure your [`OGRoot`](https://github.com/mrzapp/opengui/wiki/OGRoot) object has a [`Camera`](http://docs.unity3d.com/Documentation/ScriptReference/Camera.html) component

#### Where are the tutorials and documentation?
In the [wiki](https://github.com/mrzapp/opengui/wiki)  

#### What about examples?
This repository serves as one. Just download/clone the whole thing.

#### How can I align objects relatively to the screen?
The "anchor" and "pivot" properties of the [`OGWidget`](https://github.com/mrzapp/opengui/wiki/OGWidget) and subclasses take care of that.  

#### How do I deal with different aspect ratios?
Make sure to use "anchor" and "stretch" to position your content, if you want it to be flexible.

### License
MIT
