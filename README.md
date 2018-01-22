## 教程

![thumbnail](thumbnail.png)

```
OTA 更新是指利用无线网络更新系统，禁用设备上的 iOS OTA 更新非常简单。只要按照下面提到的步骤：
```
#### 禁用OTA更新
1. 打开 Safari 并打开这个网址：[http://chinsyo.com/noota](http://chinsyo.com/noota)
2. 本网站将指向一个 iOS 配置文件，该配置文件将被下载到您的 iPhone，并在安装过程中提示您获得许可，允许安装。
3. 下载的配置文件是从 Apple TV 操作系统中提取的。可以起到防止 iOS 检查和下载 OTA 更新。
4. 一旦你安装了配置文件，重启设备，并等待开机。
5. 重启完成后，在设置 -> 常规 -> 软件更新中不会看到更新提示。

#### 文件下载链接
* [iOS10 描述文件](https://raw.githubusercontent.com/chinsyo/noota/master/iOS10_NoOTA.mobileconfig)
* [iOS11 描述文件](https://raw.githubusercontent.com/chinsyo/noota/master/iOS11_NoOTA.mobileconfig)

---
## 提示

#### 关闭自动下载
如果您希望正常执行 OTA 检查更新，但不自动下载，只需导航到设置 -> iTunes Store与App Store，关闭自动下载的项目中「更新」。

#### 恢复OTA更新
如果您希望正常获得 OTA 更新，只需按照下面提到的步骤卸载您安装的描述文件即可。
* iOS11 之前，导航到设置 -> 通用 -> 设备管理。选择描述文件，然后点击「移除管理」。
* iOS11 之后，导航到设置 -> 通用 -> 描述文件。选择描述文件，然后点击「移除描述文件」。

#### 删除更新文件
如果您的 iPhone 已经下载了任何更新文件，只需按照下面提到的步骤卸载您安装的更新文件即可。
* iOS11 之前，导航到设置 -> 通用 -> 储存空间与 iCloud 用量，然后点击管理储存空间。选择 OTA 更新文件，然后点击「删除」。
* iOS11 之后，导航到设置 -> 通用 -> iPhone 储存空间。选择 OTA 更新文件，然后点击「删除」。

---
[给我写信](https://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=lPf8-frn7fvU5eW69-v5)
