# 快看漫画沉浸式品牌概念页

一个以「撕开分镜，进入下一格」为核心视觉命题的单页面品牌体验。项目使用纯 HTML、Tailwind CSS CDN、GSAP / ScrollTrigger、Three.js 与少量原生 JavaScript，可直接在现代浏览器中打开。

> 本项目是非官方视觉与交互概念提案，与快看漫画及其关联公司不存在隶属、合作或背书关系。快看漫画名称、商标及相关品牌资产归其权利人所有；页面中的三位角色均为本项目生成的原创概念设定，不对应任何现有漫画 IP。

## 特色

- Three.js 粒子与响应式赛博网格首屏
- 三章节固定滚动叙事
- 桌面端横向角色档案与移动端滑动卡片
- 卡片 3D 悬浮、磁吸按钮、故障字效与数字计数
- 官方网站与 App 下载二维码
- 桌面端、移动端与 `prefers-reduced-motion` 适配

## 运行

直接打开根目录的 `index.html` 即可。页面通过 CDN 加载字体、Tailwind CSS、Three.js、GSAP 和二维码脚本，因此首次打开需要网络连接。

也可以启动任意静态文件服务器：

```bash
python3 -m http.server 8000
```

随后访问 `http://localhost:8000`。

## 目录

```text
.
├── index.html
├── assets/
│   ├── hero-street-courier.jpg
│   ├── card-signal-hacker.jpg
│   └── card-biomech-fighter.jpg
├── DESIGN_SPEC.md
├── LICENSE
└── README.md
```

## 设计资料与数据口径

- 视觉方向参考 [KPR Verse](https://kprverse.com/) 的全屏叙事、界面框架与大字号排版，但未复制其标志、角色或专有设计。
- 快看官方下载入口：[kuaikanmanhua.com/webs/download](https://www.kuaikanmanhua.com/webs/download)
- 页面中的用户、创作者和全球发行数字来自 [中国新闻网 2026 年公开报道](https://www.chinanews.com/cul/2026/08-21/10681684.shtml)，并在页面中标明为公开资料口径。
- 完整配色、字体、栅格与动效规范见 [DESIGN_SPEC.md](./DESIGN_SPEC.md)。

## 开源许可

本仓库原创代码以 [MIT License](./LICENSE) 发布。原创概念图像随仓库提供，仅用于本项目的演示、学习与二次开发；通过 CDN 加载的第三方库、字体以及快看漫画相关名称和商标不属于 MIT 授权范围，详见 [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md)。MIT 许可证不授予任何快看漫画商标或品牌使用权。

