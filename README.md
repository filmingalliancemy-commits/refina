# Refina

本地 AI 素材精修（macOS，Apple Silicon）。下载最新版：https://github.com/filmingalliancemy-commits/refina/releases/latest

Refina · 本地 AI 素材精修
=========================

最低配置 / Minimum requirements
--------------------------------
• macOS 13 Ventura 或更新
• Apple Silicon（M1 / M2 / M3 / M4）。Intel Mac 不支持
• 内存 8 GB 可跑 1080p；4K 慢动作建议 16 GB 以上
• 磁盘：App 本体约 2.6 GB（AI 引擎和模型全部内置，不用另外装东西）；处理时需要临时空间
    - 1080p 慢动作 8 倍：约 5 GB
    - 4K 慢动作 8 倍：约 20 GB
    - 4K 慢动作 32 倍：约 80 GB
  临时文件处理完会自动删除
• 需要一个 Google 账号登录（只登一次，之后离线也能用）
• 网络：仅登录和同步成就时需要，所有处理都在本机完成，素材不上传

安装 / Install
--------------
1. 打开 Refina.dmg，把 Refina 拖进「应用程序」
2. 第一次打开会被 macOS 拦下（Refina 免费，没买 Apple 开发者证书）。放行一次就好：
   • macOS 15 或更新：双击被拒后，打开 系统设置 → 隐私与安全性 → 拉到最下面 → 点「仍要打开」
   • macOS 13 / 14：在 Refina 上按右键 → 打开 → 打开
   • 或者终端贴一行：xattr -cr /Applications/Refina.app
3. 之后正常双击就行。第一次启动会用 Google 登录一次

性能参考（M1 Max）/ Performance reference
------------------------------------------
• 补帧 / 慢动作：约 0.15 秒每帧
• AI 放大：约 12 秒每帧（很慢，只建议短片段和 logo/图形类素材）
• 音频去噪：约 6 倍实时速度（1 分钟音频 10 秒）
• 照片：1200 万像素一张，去噪+放大约 20 秒，人脸修复 +8 秒，上色 +10 秒
  照片 4x 放大 2400 万像素以上的图建议 16 GB 内存

注意事项 / Notes
-----------------
• 只处理未剪辑的单条素材。剪好的成片在镜头切换处会出鬼影
• 输出文件存在原素材旁边，原文件不会被改动
• 支持格式：mp4 mov m4v avi mkv mts m2ts mpg mpeg webm hevc mxf；音频 wav aif mp3 m4a aac flac caf；照片 jpg png heic tiff webp 及 RAW (dng cr2 cr3 arw nef raf)

Refina 永久免费，不锁功能。用得顺手请我喝杯 Zus Coffee。
