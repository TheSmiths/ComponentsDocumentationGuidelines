# (Set here your widget title)

(Some description of what it is and what it do)

![image title](http://link.to.your.image) (tip: an animated GIF is the best way to show it "live")


## Manifest
* Version: x.x
* Github: https://github.com/whatever...
* Author: 
* License: (not specified, Apache, MIT, ...)
* Supported Platforms: (Android, iOS, ...)


## Adding the Widget to Your Alloy Project

* In your application's config.json file you need to include the following line in your dependencies:

```
"dependencies": {
    "your.widget.project": "1.0"
}
```

*  Create a widgets directory in your app directory if it doesn't already exist.
*  Copy the your.widget.project folder into your app/widgets directory.


## Use the Widget in the View

You can add the Widget to a view by *requiring* it.

    <Widget id="myWidget" src="your.widget.project" />

Assign it an ID so you can use in your controller. E.g. `id="myWidget"` You can now access the Widget via `$.myWidget` in your controller.

```
(Some quick example of use can help)
```


## Initializing the Widget in the Controller

The Widget is off by default. Before you open your window, you need to call the Widget with the *init* method. For example:

```
$.myWidget.init();
```


## Detect a Widget event (if is your case)

You can detect a Widget event simply adding a event. (example with onChange event)

    <Widget id="myWidget" src="your.widget.project" onChange="widgetChange" />

You can now access the Widget change in your controller:

```
function widgetChange(e) {
    Ti.API.info('widget value: ' + e.value);
}
```


## Styling the Widget

In order to style the widget use any valid properties for [Ti.UI.View object](http://docs.appcelerator.com/titanium/latest/#!/api/Titanium.UI.View).

```
(Some quick example of styling can help)
```


## Initialization Parameters (if your widget support init arguments)

| Parameter | Type | Description |
| --------- | ---- | ----------- |
| param1example | *Date* | A date to start. |
| param2example | *Boolean* | Set true to show whatever. |


## Accessible Methods (if your widget have any)

| Method | Description | Example |
| ---------- | ---- | ----------- |
| method1() | Description one. | `$.myWidget.method1();` |
| method2(param) | Description two. | `$.myWidget.method2(value);` |


## Localization (if you work with texts, will be good to support localization also)
