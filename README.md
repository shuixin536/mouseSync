# mouseSync

## 开发的过程请参考我的[博客][1]

让一台Mac的键盘通过蓝牙成为另一台设备的键盘，市面上有很多，但让Mac的触摸板/鼠标成为另一台Mac的触摸板/鼠标却很少（我没有发现，如果有请issue）。
考虑到iMac关闭了纯显示器模式，所以mouseSync出现了。为使用MacBook和iMac协同工作的人制作。

=== 2017-09-29日**重大更新** ===
为应用添加了logo。

mouseSync现已支持**drag操作**，散花！
![][image-1]


=== 2017-09-28日更新 ===

**防止鼠标误操作**

限制鼠标只能在距离屏幕边缘50像素的范围内移动，防止鼠标进入dock栏和顶栏。

限制仅在程序主窗口内可用，在其他程序或桌面不可用，防止误操作。

=== 2017-09-22日更新 ===

增加了对触摸板上下/左右滑动手势的支持。demo url:https://syy.freep.cn/588778/demo922.gif

![][image-2]

=== 2017-09-21日更新 ===

增加了对鼠标双击事件的支持。demo url: https://syy.freep.cn/588778/demo2.gif

![][image-3]

=== 2017-09-20日更新 ===

鼠标可以响应move、单击、右击事件。demo url: https://syy.freep.cn/588778/demo1.gif

请注意demo中MacBook Air与MacBook Pro光标移动位置。

![][image-4]

[1]:	http://zhihaozhang.github.io/2017/09/23/%E8%AE%A9iMac%E4%B8%8EMacBook%E9%AB%98%E6%95%88%E5%8D%8F%E5%90%8C%E5%B7%A5%E4%BD%9C%E2%80%94%E2%80%94mouseSync%E5%BC%80%E5%8F%91%E5%BF%83%E5%BE%97/

[image-1]:	https://syy.freep.cn/588778/dragdemo.gif
[image-2]:	https://syy.freep.cn/588778/demo922.gif
[image-3]:	https://syy.freep.cn/588778/demo2.gif
[image-4]:	https://syy.freep.cn/588778/demo1.gif