# DoubanFM
使用Qt5构建的豆瓣音乐Linux桌面端。

![DoubanFM](https://raw.githubusercontent.com/sbwtw/doubanFM/master/screenshot/MainWindow.png)

## 功能
- [x] 使用豆瓣帐号登录
- [x] 歌曲播放及基本控制
- [ ] 加红心、删除等操作
- [x] 最小化到系统托盘
- [ ] 歌曲保存到本地
- [ ] 资源缓存
- [ ] 离线播放
- [x] 独立的歌词窗口
- [x] 歌词窗口锁定(不接收鼠标事件)
- [ ] 歌词窗口切换动效
- [ ] 切换音乐频道
- [ ] 收藏频道
- [ ] 支持Fn媒体热键

## 控制
DoubanFM 为保持与豆瓣网页版一样简洁的显示界面，功能控制由快捷键实现。
|快捷键|功能|备注|
|------|----|----|
|L|显示/隐藏歌词|Lyric|
|C|显示/隐藏频道窗口|Channel|
|W|解锁歌词窗口|歌词窗口可以拖动移动1次|
|Esc|隐藏主窗口|隐藏到托盘|
|Esc+Esc|退出程序|双击Esc退出|

## Qt依赖
Qt5-core Qt5-gui Qt5-widgets Qt5-multimedia Qt5-network Qt5-x11extras
## 第三方库
X11 Xext

## 编译
```
git clone git@github.com:sbwtw/doubanFM.git
cd doubanFM/
mkdir build
cd build
qmake ..
make -j4
./DoubanFM
```

## 安装
### 默认安装为 /usr/bin/DoubanFM
```
make install
```
