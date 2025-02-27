`2023.1.27 v0.1.0-alpha.1`
1. !!!【功能】插件更新，升级到新版本之后原有插件完全不兼容；更新后卸载原有插件，然后更新订阅即可（具体看公众号示例）
2. 【功能】新增功能“倍速播放”
3. 【功能】重写了插件订阅的逻辑，现在应该会更合理一点点
4. 【功能】删除本地文件之前增加二次确认提醒
5. 【功能】增加了一些无关紧要的分享
6. 【样式】换了个logo，丑的更直白一些
7. 【样式】调整了一些样式（如播放页的模糊和透明度、歌词样式等）
8. 【样式】专辑描述文字默认6行，点击可以展开或折叠
9. 【修复】修复部分情况下无法下载的问题
10. 【插件】大量插件有更新，更新到此版本后更新订阅即可

`2023.1.8 v0.0.1-alpha.13`
1. 【功能】主页入口增加“榜单”
2. 【功能】歌单页新增“编辑歌单信息”，可以修改歌单名称和歌单封面
3. 【修复】修复了一个会导致播放音乐时拖拽排序卡顿的问题，做了一些其他优化
4. 【插件】部分插件有更新，可以在侧边栏更新

`2022.12.25 v0.0.1-alpha.12`
1. 【功能】增加“单击搜索结果中单曲tab”时的行为配置
2. 【功能】增加调试配置及调试面板，可用于查看插件的错误信息
3. 【修复】修复部分情况下本地音乐中断时无法继续播放的问题
4. 【修复】尝试修复扫描本地音乐，音乐文件太多时可能卡死的问题

`2022.12.11 v0.0.1-alpha.11`
1. 【功能】完善音质功能
2. 【功能】更新下载功能，支持根据音质下载文件；修复一些小问题
3. 【功能】新增播放时被打断的设置，可设置为暂停或者暂时降低音量
4. 【优化】调整侧边栏样式，侧边栏新增“定时关闭”功能
5. 【优化】本地音乐读取歌词时，会自动读取同目录下的同名lrc文件作为歌词
6. 【修复】修复安装插件时误弹安装失败提示的问题
7. 【修复】修复部分情况下本地文件删除失败的问题
8. 【修复】修复本地音乐在通知栏不显示音乐标题的问题
9. 【插件】示例插件仓库中migu有更新（支持音质），需要可自行更新

`2022.12.4 v0.0.1-alpha.10`
1. 【功能】支持自定义下载路径
2. 【功能】支持插件排序（也就是搜索结果的排序）
3. 【功能】增加音质相关的配置
4. 【优化】弹窗、浮层的性能优化，页面嵌套较深时卡顿的情况应该会好一点
5. 【优化】拖拽排序，比上个版本手感应该会好一点
6. 【修复】修复在歌词页清空播放列表时白屏的问题

`2022.11.20  v0.0.1-alpha.9`
1. 【功能】本地音乐读取内嵌歌词
2. 【功能】批量编辑页新增了凑合能用的拖拽排序
3. 【功能】歌曲详情浮层新增凑合能用的定时关闭
4. 【功能】添加到歌单时可以新建歌单
5. 【功能】本地音乐扫描支持外置sd卡；支持导入aac格式
6. 【优化】优化播放列表浮层拉起时的锚定
7. 【修复】修复更新弹窗无法滚动的问题
8. 【修复】修复安卓12状态栏概率不沉浸的问题
9. 【修复】修复安卓12、13播一首就停的问题
10. 【插件】示例插件有更新，可以删掉原有插件重新导入

`2022.11.13  v0.0.1-alpha.8`
1. 【功能】侧边栏插件设置新增“订阅插件”功能，订阅之后直接点击“更新插件”即可更新，不需要清空重装了
2. 【功能】本地音乐读取内置封面
3. 【功能】本地音乐歌单支持批量删除（不删除源文件）
4. 【优化】重写导入本地音乐的逻辑，支持多选文件夹；修复部分机型重启应用时本地音乐消失的问题（可能需要删除后重新导入）；支持导入flac,wav,wav,m4a,ogg等格式
5. 【优化】重写播放列表浮层，拉起时会锚定到当前正在播放的歌曲
6. 【优化】调整部分逻辑，可能会减少音频卡顿时卡死的情况
7. 【修复】修复歌曲详情页进度条不连续的问题
8. 【修复】修复某些情况下无法关联歌词的问题
9. 【修复】修复正在播放的歌曲无歌词时，进入歌词页白屏的问题
10. 【插件】示例插件有更新，可以删掉原有插件重新导入

`2022.10.30  v0.0.1-alpha.7`
1. 新增功能：历史记录一键清空
2. 新增功能：歌手页、本地歌单页支持批量编辑
3. 修复移动网络下无法播放本地音乐的问题
4. 样式优化&修复：toast提示显示异常、侧边栏样式优化、歌单内序号显示不全、【关于】页无法滑动
5. 之前使用的拖拽排序组件在列表较大时有很严重的性能问题，会导致卡顿甚至白屏，因此批量编辑页暂时去掉了拖拽排序，后续会重新加上
6. 插件：网易云插件支持导入201首以上的歌单，可以去侧边栏更新，插件新增酷狗源，可以去对应github仓库查看。

`2022.10.22  v0.0.1-alpha.6`
1. 重要!! v0.0.1-alpha.5以前的版本无法通过app正常更新，请在gitee/github发布页下载最新版本(v0.0.1-alpha.6)，或QQ群自取；
2. 导入本地音乐时，如果未识别本地音乐文件，则会使用文件名作为音乐名；
3. 自建歌单、专辑详情页增加批量选择功能，可点击右上角查看(歌曲较多时可能有点卡，后续优化)；使用方式：选中歌曲可进行下一首播放/加入歌单/下载/删除，长按拖动进行排序；删除/排序后点击保存按钮方可生效
4. 调整歌单内歌曲编号字体大小；

`2022.10.16  v0.0.1-alpha.5`
1. 新增功能：导入本地音乐文件
2. 从网络源安装的插件可在插件页直接更新
3. 调整下载逻辑

`2022.10.06  v0.0.1-alpha.4`
1. 修复专辑详情页没有loading的问题
2. 为插件新增Cookie管理器
3. 优化播放页的显示
4. 新增一键卸载全部插件的功能

`2022.10.04  v0.0.1-alpha.3`
1. 修复设置页无法滚动的问题
2. 修复播放结束时可能暂停的问题

`2022.10.03  v0.0.1-alpha.2`
1. 插件协议更新，需要重新安装插件
2. 支持批量导入插件
3. 新增清空播放列表功能
4. 优化搜索结果面板和播放专辑逻辑

`2022.10.02`
测试版本出现啦！撒花