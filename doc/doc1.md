##数据绑定
很显然初学者都是从第一个数据绑定开始的，以前数据绑定需要写一大堆js绑定，比如老徐文中提到的
>界面上有个输入框，然后有另外一个地方，要把这个文本原样显示出来
在没有angularjs的情况下就需要手写一个input侦听，然后修改div的innerHTML，但是有了angularjs后一切变得那么和谐。
```HTML
<input type="text" ng-model="a"/>
<div>{{a}}</div>
```
