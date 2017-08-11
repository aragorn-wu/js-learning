页面加载的时候，浏览器会创建文档对象模型(Document Object Model)。
HTML DOM模型被构造为对象的树，如下图：
![](../pictures/ct_htmltree.gif)
通过可编程对象模型，javaScript可以创建动态的HTML，具体如下：
<ol>
<li>改变html元素</li>
<li>改变html属性</li>
<li>改变css样式</li>
<li>对页面中的事件做出反应/li>
</ol>

此外，javaScript可以通过如下方式来查找html元素：
<ol>
<li>通过id查找html元素</li>
var x=document.getElementById("intro");
<li>通过标签名查找html元素</li>
var y=x.getElementsByTagName("p");
<li>通过类名查找html元素</li>
</ol>