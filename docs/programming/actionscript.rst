==================
ActionScript
==================


关于TextField的按钮功能
===========================

当一个动态的TextField位于一个sprite或者MovieClip对象中时，
会出现不能正确显示可点击的手形鼠标的问题。可按照如下方法
加以解决：

（假如MC中有TF对象）

::

    MC.buttonMode = true;
    MC.mouseChildren = false;

