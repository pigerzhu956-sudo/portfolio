# 朱利锋个人网站 V1

基于原作品集模板进行内容迁移的静态单页个人网站。保留原布局、响应式与动画，提供中英文切换、个人经历、AI 实践项目、奖项、联系方式及简历下载。

## 本地查看

可以直接打开 `index.html`。建议在项目目录启动静态服务后检查下载功能：

```powershell
python -m http.server 8765 --bind 127.0.0.1
```

浏览器访问 `http://127.0.0.1:8765/`。

## 文件说明

- `index.html`：页面、样式、双语内容与交互。
- `assets/avatar.png`：本人头像。
- `assets/resume.pdf`：本人简历，直接引用，未改动 PDF 内容。
- `assets.js`：兼容说明文件，旧 Base64 数据已清理，页面不再加载。
- `images/`：原模板资源暂留，V1 不引用。
- `PROFILE.md`、`CODEX_HANDOFF.md`：个人资料与迁移说明。
- `.nojekyll`：保留静态发布标记。

## 待补内容

- 凌岳数科正确入职年月：已确认入职，页面暂不展示日期。
- 两个 AI 项目的 Demo、仓库链接与真实截图。
- 公益广告三等奖的年份、作品名与证书；其余四张证书已接入。
- 学术模块暂隐藏；证书轮播已使用本人四张证书恢复，支持点击放大。

## 来源与发布

原模板设计：Jing Xu；视觉参考为 https://double-bean.github.io/portfolio/ 。保留原设计署名。
目标公开地址：https://pigerzhu956-sudo.github.io/portfolio/ 。保留原模板设计署名。

## GitHub Pages

Settings → Pages → Deploy from a branch → main → / (root) → Save。
发布仅包含网站运行文件；本地交接资料及原作者未使用图片不提交。
省级一等奖采用小图预览与无损全尺寸 WebP 放大，原 PNG 本地保留。
