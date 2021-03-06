---
title: Custom Hyperlinks
id: customlinks
layout: manual
description:  Like many terminals, Tilix allows clicking on a specific content to perform actions. For example, clicking on a hyperlink opens it in teh browser. Tilix takes this a step further and allows the user to define custom links and actions based on regular expressions.
---
Tilix allows custom hyperlinks to be defined using regular expressions. These links can then be clicked on to launch an application passing information from the match to the application.

When configuring the application to be launched, the token ```$0``` can be used to represent the match obtained from the regular expression. If the regular expression includes groups then ```$1``` is the first group, ```$2``` the second group, etc.

Here is a screenshot showing an example of using this feature to launch gedit with the filename and line number based on a regular expression that includes two groups.

![]({{site.baseurl}}/assets/images/manual/links.png)
