# Protobuild.Manager

A cross-platform GUI manager for Protobuild modules.  It's goals are:

  * Make it easy to create cross-platform projects from templates
  * Allow developers using Protobuild to easily change the platform they're working on

This is extremely work-in-progress, but here's a video that demonstrates changing the platform through the graphical interface.  You'll notice that the tool communicates directly with Visual Studio to automatically save everything and re-open the newly generated project files as needed (**[click to play video](https://www.youtube.com/watch?v=v7j505P5AkM)**):

[![Video of switching platforms in Visual Studio](http://img.youtube.com/vi/v7j505P5AkM/0.jpg)](https://www.youtube.com/watch?v=v7j505P5AkM)

It has a recent items, project opening and new project creation template that will be familar to users of other game development tools:

![Opening screen](http://i.imgur.com/IlsCmEf.png)

It can be built for all desktop platforms, and produces just a single executable that you can distribute to your users.

It can also be branded, so you can set specific project templates that should be offered to users, and so you can remove any Protobuild naming throughout the application.
