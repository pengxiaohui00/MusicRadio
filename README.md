
# 项目标题：MusicRadio


https://pengxiaohui00.github.io/MusicRadio/code/index.html


## 项目功能介绍：
1.这是一个简单的音乐电台，拥有41种不同的音乐风格类型供你选择并随时切换。

2.还可以选择你喜欢的音乐，并添加到我的最爱歌单中，并本保存到浏览器本地，下次登入一直保存你喜欢的歌曲，除非你主动删除。

3.还有很酷的歌词提示，且具有旋转效果。

4.当然切换下一首，播放，暂停，时间，进度条显示等简单音乐播放器的一切效果它都有。

5.另外它还有满屏显示和响应式页面哦。

## 项目技术细节介绍：

1.使用jQuery库来方便并大大的简化了代码。

2.通过Jonsp的方法请求数据，解决了同源策略的问题。

3.通过自定义事件的思路，使整体分为底部切换分类，和歌曲播放等两个模块并互不干扰。

4.通过模块化，封装函数的思路，先初始化，绑定事件，具体事件功能，请求数据，渲染数据等等，增加代码逻辑性，和复用性，极大简化的代码，并且减少了全局变量污染，很方便后期调试。

5.满屏通过设置把高度设置成100%,把高度通过设置vh，宽度通过媒体查询，实现响应式。

6.通过JQuery动画animate与DOM事件结合实现切换音乐风格类型，并通过加锁方法优化了功能。

7.通过audio对象的方法与DOM事件结合，实现音乐切换下一首，，播放，暂停，时间显示。

8.百度外链不允许他人播放，通过设置referrer，页面来源的请求头为空，解决bug.

9.监听音乐播放时状态，在音乐播放时显示相应的时间，进度条；通过定时器实现时时更新播放状态。

10.歌词匹配，通过把歌词字符串切割成数组，通过正则表达式匹配对应时间，转化成对象，属性为时间，值为对应歌词，然后在播放状态更新时添加对应歌词。

11.歌词旋转，音乐播放时把对应每行歌词，分割成单个字然后被span包含，通过定时器，给每个字依次添加animate.css中对应的旋转样式。

12.把你选中喜欢的歌曲，收集到你最爱的歌单上，通过localStorage存储到浏览器本地。


## 项目收获；熟悉了一个完整项目的思路和流程，并通过实现功能和测试功能debug，复习与总结相关知识点。

## 技术栈关键字：jQuery、CSS3、响应式
