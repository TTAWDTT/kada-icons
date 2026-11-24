# 咔嗒 · Kada Icons

82 枚用 AI 绘制的贴纸风图标，每枚都有 24、48、96 像素的透明 PNG。最初的一批来自 [oh-bilibili](https://github.com/TTAWDTT/oh-bilibili)。现在也可以拿来做文件列表、成员管理、工具栏和出错提示。

[下载整套图标](https://github.com/TTAWDTT/kada-icons/releases/download/v0.2.0/kada-icons-v0.2.0.zip) · [看新补的四组图标](previews/additions.png) · [看 24 像素实际大小](previews/size-24.png)

![咔嗒图标总览](preview.png)

## 图标

### 频道

[发现](icons/wink-tv.png) · [动态](icons/feed-paperplane.png) · [消息](icons/msg-envelope.png) · [排行榜](icons/rank-rosette.png) · [综合热门](icons/popular-flame.png) · [入站必刷](icons/precious-ticket.png) · [每周必看](icons/weekly-calendar.png) · [直播](icons/live-camera.png) · [番剧](icons/bangumi-clapper.png)

### 我的

[个人中心](icons/profile-badge.png) · [历史](icons/history-clock.png) · [收藏夹](icons/favorite-folder.png) · [稍后再看](icons/later-screen.png) · [关注](icons/following-pair.png) · [赞过的视频](icons/liked-thumb.png) · [曲库](icons/library-record.png) · [已下载](icons/download-tray.png) · [设置](icons/settings-dial.png)

### 投稿与服务

[投稿](icons/upload-cloud.png) · [创作中心](icons/creator-pen.png) · [会员购](icons/shop-parcel.png) · [漫画](icons/comic-book.png) · [赛事](icons/event-cup.png)

### 分区

[动画](icons/animation-cels.png) · [音乐](icons/cassette.png) · [游戏](icons/handheld.png)

### 基础操作

[搜索](icons/search.png) · [返回](icons/back.png) · [前进](icons/forward.png) · [刷新](icons/refresh.png) · [关闭](icons/close.png) · [更多](icons/more-horizontal.png) · [筛选](icons/filter.png) · [添加](icons/plus.png)

### 内容操作

[完成](icons/check.png) · [链接](icons/link.png) · [分享](icons/share.png) · [编辑](icons/edit.png) · [复制](icons/copy.png) · [删除](icons/trash.png) · [下载](icons/download-device.png) · [上传](icons/upload-arrow.png)

### 沟通与媒体

[通知](icons/notification-bell.png) · [评论](icons/comment.png) · [喜欢](icons/heart.png) · [日历](icons/calendar.png) · [播放](icons/play.png) · [暂停](icons/pause.png) · [音量](icons/volume.png) · [全屏](icons/fullscreen.png)

### 文件和文件夹

[文件夹](icons/folder.png) · [打开文件夹](icons/folder-open.png) · [新建文件夹](icons/folder-add.png) · [文件](icons/file.png) · [文本文档](icons/file-text.png) · [图片文件](icons/file-image.png) · [压缩文件](icons/file-archive.png) · [附件](icons/attachment.png)

### 用户和权限

[用户](icons/user.png) · [群组](icons/users.png) · [添加成员](icons/user-add.png) · [移除成员](icons/user-remove.png) · [已锁定](icons/lock.png) · [已解锁](icons/unlock.png) · [钥匙](icons/key.png) · [已验证](icons/shield-check.png)

### 加载和出错

[加载中](icons/loading.png) · [等待中](icons/hourglass.png) · [请求超时](icons/timeout.png) · [警告](icons/warning.png) · [出错](icons/error.png) · [网络断开](icons/offline.png) · [服务异常](icons/server-error.png) · [无权访问](icons/access-denied.png)

### 空页面和状态

[收件箱为空](icons/inbox-empty.png) · [没有搜索结果](icons/search-empty.png) · [列表为空](icons/list-empty.png) · [图片缺失](icons/image-missing.png) · [成功](icons/success.png) · [提示](icons/info.png) · [同步完成](icons/sync-complete.png) · [草稿](icons/draft.png)

## 使用

要按名字找图，见[中文名称、文件名和各尺寸路径](icons.json)。

把需要的 PNG 复制到自己的项目里。下面的例子把图标放在按钮文字旁边，显示宽度为 24 像素。

```html
<button type="button">
  <img src="./sizes/24/favorite-folder.png" width="24" alt="">
  收藏夹
</button>
```

## 画法与新增图标

画布、轮廓、颜色和 24 像素检查规则写在 [STYLE.md](STYLE.md)。新增图标需要同时补上三档尺寸和 `icons.json`。

## 授权

本仓库的图标和说明采用 MIT-0 许可。可以用于个人或商业项目，也可以修改和再分发，署名自愿。[许可全文](LICENSE)
