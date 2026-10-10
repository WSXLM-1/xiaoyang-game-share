小杨游戏分享 · 网站文件

背景已改为上传的视频 assets/background-video.mp4，并设置 autoplay、muted、loop、playsinline，支持静音自动播放并无限循环。动态雨滴层仍叠加在视频上。

使用方法：
1. 解压 ZIP，双击 index.html 预览（部分浏览器对本地视频自动播放可能有限制，建议通过本地静态服务器或部署后测试）。
2. 用记事本或 VS Code 打开 index.html。
3. 搜索 `const DESTINATIONS = {`，分别设置四个选项的真实网址：
   pack: "https://你的整合包网址",
   resources: "https://你的游戏资源网址",
   tools: "https://你的工具网址",
   emulator: "https://你的模拟器网址"
4. 上传整个文件夹到支持静态网页的网站托管服务。请保持 index.html 与 assets 文件夹中的头像、背景图片和 background-video.mp4 的相对位置不变。
