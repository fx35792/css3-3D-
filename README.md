# css3-3D-
每天进步一点点
一个css3-3D特效的小例子
一个字体翻转的效果
##知识点一：transition的用法
transition:<属性名称>+<时间>+<动画效果><br>
```bash
#eg:	-webkit-transition:background-color 1s ease;
```
<属性名称>:width、height、-webkit-transform等等<br>
<时间>:1s 、2s、3s等等<br>
<动画效果>:linear、ease、ease-in、ease-out、ease-in-out等等 <br>
##知识点二：创建3D场景
###1.创建3D场景
-webkit-perspective:800;
-webkit-perspective-origin:50% 50%;
###2.设置3D场景（使用transform属性）
为了让浏览器知道我们使用时3D场景 我们需要加入：
-webkit-transform-style:-webkit-preserve-3d;
或者
-webkit-transform-style:preserve-3d;
#####-translate
* translateX(x px)
* translateY(y px)
* translateZ(z px)
#####-translate
* rotateX(x deg)
* rotateY(y deg)
* rotateZ(z deg)
###3.设置3D场景（使用transform-origin属性调整旋转中心）
####-x轴
* left
* center
* right
####-y轴
* top
* center
* bottom
####-z轴
* length px
