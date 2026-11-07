# CATHY · 个人设计作品集

静态作品集网站，包含首页、中后台系统、大屏可视化、AI 智能体、APP 小程序、AIGC 短片和关于我。

图片、视频与标识字体随仓库保存。视频静音自动循环播放，不显示播放控件。

## 本地预览

在仓库目录运行：

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

访问 http://127.0.0.1:4173/ 。

## GitHub Pages

使用分支发布：在仓库 Settings → Pages 中选择 **Deploy from a branch**，分支为 **main**，目录为 **/(root)**。

项目站点路径为 `https://chenjinwen00.github.io/portfolio1/`，以 GitHub Pages 最终返回的发布地址为准。

页面使用相对资源路径，兼容 `/portfolio1/` 子路径部署。
