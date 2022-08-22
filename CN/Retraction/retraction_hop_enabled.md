回抽时 Z 抬升
====
### **参数描述**
喷嘴在每次回抽时都会抬升（或打印平台降低），与打印件之间形成一定距离。喷嘴在抬升后，高度略高于已打印部件，这样，喷嘴在经过打印件时就不会碰到已打印的部分。

![Moving up when Z hops are enabled](../images/retraction_hop_enabled.svg)

### **参数使用**
* 此设置可防止喷嘴在空驶过程中碰到打印件。喷嘴一旦碰到打印件就会留下明显的疤痕，使用此设置可以让打印件壁看起来更美观。
* 如果材料在空驶过程中从喷嘴中渗出，渗出物会挂在喷嘴的下一个停靠位置。通常喷嘴在空驶结束后会停靠在模型内部填充上，这样渗出物形成的凸点就可以被隐藏在模型内部，减少对打印件表面的影响。
* 喷嘴碰到模型表面的凸点可能会撞翻打印件，启用此设置可以让打印过程更顺利。

但让喷嘴一直上下移动会增加打印时间，还会更快地磨损打印机的 Z 轴，具体磨损情况取决于打印机的设计。