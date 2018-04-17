# unity3d-homework4
打飞碟
* 程序规则：写个用鼠标打飞碟的游戏。 
游戏要分多个 round ， 飞碟数量每个 round 都是 n 个，但色彩，大小；发射位置，速度，角度，每次发射数量可以变化。 
游戏过程中，仅能创建 n 个飞碟， 且不容许初始化阶段生成任何飞碟。 飞碟线路计算请使用 mathf 类。 向下加速度 a 是常数。 飞碟被用户击中，则回收。并按你定义的规则计算分数。飞碟落地（y < c）,则自动回收。

预设部分
* 程序中用到的对象如下：

飞碟：创建一个Cylinder，将该物体的scale.y改成0。08，加入预设。

地板：新建一个Plane进行拉伸，加上贴图后即可。

文本框组：在 Component的UI里新建text，并设置三个文本 Main Text,Round Text,Score Text，分别表示主文本，当前回合数，当前分数。

代码已上传，视频链接：
<iframe height=498 width=510 src='http://player.youku.com/embed/XMzU0NTM1MzQ3Mg==' frameborder=0 'allowfullscreen'></iframe>
