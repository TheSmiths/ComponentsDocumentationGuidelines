# Project title [![Titanium](http://www-static.appcelerator.com/badges/titanium-git-badge-sq.png)](http://www.appcelerator.com/titanium/) [![Alloy](http://www-static.appcelerator.com/badges/alloy-git-badge-sq.png)](http://www.appcelerator.com/alloy/)

This widget for the [Appcelerator](http://www.appcelerator.com) Titanium Alloy MVC framework provides _[describe project here: what's its story/purpose?]_

## Preview
_Protip:_ an animated GIF is the best way to show it "live"  

![Example gif from To.BounceView](http://zippy.gfycat.com/DarlingFairHornet.gif)  
_Example gif from To.BounceView_

## Quick Start

### Get it [![gitTio](http://gitt.io/badge.png)](http://gitt.io/component/[YOUR PROJECT ID])
Download this repository and install it:

* In your application's config.json file, include the following line in your dependencies:

```json
"dependencies": {
    "my.project.id": "1.0"
}
```

*  Copy the `your.widget.project` folder into your `app/widgets` directory.


**Or simply use the [gitTio CLI](http://gitt.io/cli)**:

`$ gittio install my.project.id`

### Use it

* Require the widget in a view:

**file1.xml**
```xml
<Widget id="myProjectId" src="my.project.id" />`
```
Which create a reference in your controller, accessible via: `$.myProjectId`

* Or, require it directly in a controller :

```javascript
var myProjectId = Alloy.createWidget("my.project.id");
```

Then you can [DO THIS] or [DO SOMETHING ELSE].
```
Some quick examples of use are always helpful
```


## Documentation
### Initialization
Before opening your window, call the project's *init* method. For example:

```
$.myProjectId.init(options);
```

Initialization parameters are:  

| Parameter     | Type      | Description               |
| ------------- | --------- | ------------------------- |
| param1example | *???*     | ...                       |
| param2example | *???*     | ...                       |


## Public methods
Here is a list of all accessible methods and the associated expected behaviour:

| Method         | Description               |
| -------------  | ------------------------- |
| method1example | ...                       |
| method2example | ...                       |


## Events
You can listen for events by simply adding an event listener:

* In an Alloy view:
```xml
<Widget id="myProjectId" src="my.project.id" onChange="widgetChange" />
```

* In an Alloy controller (backbone event):
```javascript
$.myProjectId.on("change", widgetChange);
```

You can now bind the change listener in your controller:

```javascript
function widgetChange(e) {
    Ti.API.info('widget value: ' + JSON.stringify(e));
}
```

### Supported events
Here is a list of all supported events and the associated expected behaviour:

| Event         | Description               |
| ------------- | ------------------------- |
| event1example | Triggers when..., contains properties..., used for... |
| event2example | Triggers when..., contains properties..., used for... |


## Customization
* How to apply custom styles to the project?
* What kind of custom models are supported (provide structure)?
* Which public properties can be accessed (provide list)?

******************************************

## TODO / Ideas for improvement
Feel free to improve this widget by forking, submitting pull requests or creating issues.  
Here are my ideas:

* It works, now make it awesome.
* ...
* ...

## Changelog
* 1.0 First version

## Dependencies
* [...]()
* [...]()

## Licences
This project is licensed under [LICENSE]. Please read the [LICENSE FILE] file for more information about this license.  

The [DEPENDENCY] is licensed under the [LICENSE](http://url.to.license). You can get it [here](http://url.to.product).  

Appcelerator, Appcelerator Titanium and associated marks and logos are trademarks of Appcelerator, Inc.  
Titanium is Copyright (c) 2008-2015 by Appcelerator, Inc. All Rights Reserved.  
Titanium is licensed under the Apache Public License (Version 2).  
