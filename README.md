Color Brewer Library
=========

This is a simple library to use the Color Brewer more easily.
If you don't know color brewer please [check it out first.][1]
  
How to use
----------

Use the enumeration to get the Nature of Data and Color Scheme.
choose the number of data classes (note that the number of data classes varies depending of nature of data).

Example
--------------

```sh
var colorBrew = window.ColorBrewer;
var colorArray = colorBrew.getColor(colorB.options.DIVERGING.RdBu,3);
```
[<i class="icon-share"></i> plnker example][2]


[1]:http://colorbrewer2.org/
[2]:http://plnkr.co/edit/1UqWkE?p=preview
