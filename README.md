# wx-gotripping
<h2><strong>需求分析</strong></h2>
<ol>
 	<li>
<h3 class="reader-word-layer reader-word-s1-1">业务分析</h3>
在现在社会中的旅游app中，充斥着太多的广告以及一些繁杂的信息，无法使用户能很好的很迅速的获得对于景点的期待的回应。因此我们想做一个类似于晒朋友圈一样的晒驴友们在旅游景点的活动以及感受，让用户们能够身临其境的感受各个景点，去选择自己喜欢的地方。</li>
 	<li>
<h3 class="reader-word-layer reader-word-s1-1">用户分析</h3>
本产品主要针对各位驴友们，给他们展示其他人在各个景点的驴友活动、感受以及小动态。还包括对景点的简单介绍和相关需求的推荐。</li>
 	<li>
<h3 class="reader-word-layer reader-word-s1-1">功能分析</h3>
<h4>（1）旅游小动态展示板块</h4>
以瀑布形式展示驴友们写的关于他们旅游的动态，选择具体一项后能够查看他在旅游期间写的所有动态，还能查看别人对其的点评以及点赞情况
<h4>（2）旅游景点推荐板块</h4>
此版块主要为用户推荐不同时间内的最佳旅游景点，选择具体一项后能够查看该地的旅游景点，还能够查看该地的住宿、休闲、购物等信息
<h4></h4>
</li>
 	<li>
<h3 class="reader-word-layer reader-word-s1-1">性能分析</h3>
本应用基于微信小程序。</li>
</ol>
<h2><strong>目标</strong></h2>
<ol>
 	<li>
<p class="reader-word-layer reader-word-s3-15">基本要求：需要包括的主要功能</p>

<h4>（1）动态的展示功能</h4>
<h4>（2）评论点赞功能</h4>
<h4>（3）地区展示列表</h4>
<h4>（4）景点、住宿、购物等信息列表</h4>
</li>
 	<li>
<p class="reader-word-layer reader-word-s3-15">开发目标：预期的展现形式</p>
<img class="alignnone size-thumbnail wp-image-10409" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获5-90x150.png" alt="" width="90" height="150" /> <img class="alignnone size-thumbnail wp-image-10408" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获4-89x150.png" alt="" width="89" height="150" /> <img class="alignnone size-thumbnail wp-image-10407" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获3-90x150.png" alt="" width="90" height="150" /> <img class="alignnone size-thumbnail wp-image-10406" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获2-89x150.png" alt="" width="89" height="150" /> <img class="alignnone size-thumbnail wp-image-10405" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获1-89x150.png" alt="" width="89" height="150" /> <img class="alignnone size-thumbnail wp-image-10404" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获-2-88x150.png" alt="" width="88" height="150" /></li>
 	<li>
<p class="reader-word-layer reader-word-s3-15">应用目标：计划的应用效果</p>
<img class="alignnone size-full wp-image-10409" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获5.png" alt="" width="377" height="630" /> <img class="alignnone size-full wp-image-10408" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获4.png" alt="" width="378" height="638" /> <img class="alignnone size-full wp-image-10407" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获3.png" alt="" width="379" height="633" /> <img class="alignnone size-full wp-image-10406" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获2.png" alt="" width="379" height="637" /> <img class="alignnone size-full wp-image-10405" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获1.png" alt="" width="377" height="634" /> <img class="alignnone size-full wp-image-10404" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获-2.png" alt="" width="375" height="640" /></li>
</ol>
<h2><strong>总体设计</strong></h2>
系统业务流程及描述（可以流程图的方式呈现）

<img class="alignnone size-full wp-image-10492" src="http://112.74.62.56/wp-content/uploads/2017/07/未命名文件-1.png" alt="" width="745" height="539" />
<h2><strong>详细设计</strong></h2>
系统各个功能模块界面展示
<h4>（1）用户旅游小记列表</h4>
<img class="alignnone size-full wp-image-10404" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获-2.png" alt="" width="375" height="640" />
<h4>（2）用户动态展示</h4>
<img class="alignnone size-full wp-image-10405" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获1.png" alt="" width="377" height="634" />
<h4>（3）用户信息界面</h4>
<img class="alignnone size-full wp-image-10563" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获7.png" alt="" width="377" height="607" />
<h4>（4）单个动态展示及点评点赞</h4>
<img class="alignnone size-full wp-image-10406" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获2.png" alt="" width="379" height="637" />
<h4>（5）旅游地区推荐</h4>
<img class="alignnone size-full wp-image-10407" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获3.png" alt="" width="379" height="633" />
<h4>（6）地区景点列表</h4>
<img class="alignnone size-full wp-image-10408" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获4.png" alt="" width="378" height="638" />
<h4>（7）地区住宿、购物等信息列表</h4>
<img class="alignnone size-full wp-image-10409" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获5.png" alt="" width="377" height="630" />
<h2><strong>功能实现</strong></h2>
<ul>
 	<li>具体文件结构<img class="alignnone size-full wp-image-10556" src="http://112.74.62.56/wp-content/uploads/2017/07/捕获6.png" alt="" width="304" height="540" /></li>
 	<li>解读每个功能模块的实现过程，并讲解一下重要部分的代码。
<h4>1、小程序首页（/pages/index）</h4>
小程序首页显示当前的旅游动态列表。在小程序开启时，会调用Api中的getHotTripList方法，从面包旅行的api中获取response。然后通过json从response中读取热门景点的标题、图片、作者、日期等信息。然后将这些信息填入到我们编写的框架结构中，形成了首页的旅游动态列表。并且定义lodamore函数，当向下滑动的调用，向api请求更多的数据，并写入框架。当点击某个目录是将会调用navigateTo函数跳转到/pages/trip中。
<h4>2、具体个人动态界面(/pages/trip、/pages/trip_list)</h4>
该页面在你选择相应的动态目录之后会跳转到此，通过getTripInfoByID来获取用户id以及id下的其他数据。页面框架由view和block组成，形成一个瀑布式的展示下滑栏。根据获得的日期的大小来排列动态的顺序，大的在上小的在下。通过点击头像能够navigateTo到/pages/user来查看用户信息，通过点击具体的某一条动态能够navigateTo到/pages/waypoint动态的具体情况，包括点赞数、点评等。
<h4>3、用户信息界面（/pages/user）</h4>
该页面在你点击了用户头像后会跳转至此，通过getTripInfoByID来获取用户id以及id下的其他数据。页面框架主要由view组成，包括用户的粉丝数、关注数以及他写过的旅行动态目录。根据获得的日期的大小来排列动态的顺序，大的在上小的在下。通过点击动态目录能够navigateTo到/pages/trip来查看动态瀑布。
<h4>4、单个动态展示及点评点赞（/pages/waypoint）</h4>
该页面在你点击了个人动态中的某一个后会跳转到此，通过getTripInfoByID来获取活动id以及id下的其他数据。页面框架主要由view和block组成，包括具体的动态信息、日期、点赞和评论等信息。日后，我们考虑将设计评论条，供用户自己写评论，点赞，然后将这些数据上传至服务器中,然后进行更新。
<h4>5、旅游地区推荐（/pages/explore）</h4>
小程序的第二个主体显示不同地区推荐的旅游地点。用方块式的摆放框架排列各个旅游地点的图片以及标题。通过点击地点图标能够navigateTo到/pages/destination来查看目标地点的具体信息。
<h4>6、 地区景点（/pages/destination）</h4>
该页面在你点击了旅游地点后跳转至此，通过getTripInfoByID来获取活动id以及id下的其他数据。页面框架主要由view组成，分为上下两部分，上部分包含地区名称和图片，下半部分包含该地区景点。通过点击旅行地点图标能够navigateTo到/pages/poi_list来查看目标地点的具体信息,包括景点、食宿、购物等推荐。
<h4>7、地区住宿、购物等信息列表</h4>
该页面在你点击了旅游地点图标后跳转至此，通过getPlacePOIByID来获取地区活动的id以及id下的其他数据，例如景点、食宿等。页面框架主要由scroll-view组成。</li>
 	<li>项目源码可托管在github上，并在此放源码链接。</li>
 	<li>一个优秀的开源项目，源码一定有丰富的注释，让后人易读且方便修改。</li>
</ul>
<h2><strong>项目演示</strong></h2>
<ul>
 	<li>项目演示可放视频链接或二维码，推荐腾讯视频哦，适合在微信里传播。</li>
 	<li>web类项目，可以利用github的项目演示功能，创建在线链接，方法参照：<a href="http://www.tuicool.com/articles/Z7nMva" target="_blank">如何在github上创建个人项目的在线演示demo</a></li>
</ul>
<h2><strong>团队故事</strong></h2>
<table style="height: 116px; border-color: #d8d8d8; background-color: #f9f9f9; width: 448px;" border="1" cellspacing="0" cellpadding="5px">
<tbody>
<tr style="height: 24px;">
<td style="width: 92px; height: 24px;"><strong>姓名</strong></td>
<td style="width: 330px; height: 24px;"><strong>职责</strong></td>
</tr>
<tr style="height: 24px;">
<td style="width: 92px; height: 24px;">洪誉</td>
<td style="width: 330px; height: 24px;">技术担当，资源协调</td>
</tr>
<tr style="height: 24px;">
<td style="width: 92px; height: 24px;">程文毅</td>
<td style="width: 330px; height: 24px;">硬件设计，创意思路</td>
</tr>
</tbody>
</table>
团队联系方式：邮箱、QQ、电话等；
团队合作过程中发生的趣事、攻克的难关。
<h2><strong>资料链接</strong></h2>
<a href="http://www.w3school.com.cn/" target="_blank"><em>w3s</em>chool 在线教程</a>
