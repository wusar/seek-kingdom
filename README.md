# Seek Kingdom · 王国围城

可破坏体素攻城场景的网页版：程序化生成王国、攻城破坏、喷火巨龙、天气与昼夜。全部场景由代码生成，无外部模型或贴图。

- 在线游玩：https://wusar.github.io/seek-kingdom/
- 本地打开：直接双击 index.html（	hree.min.js 已随仓库提供，无需联网）
- 操作：左键拖动环绕镜头，滚轮缩放，空格切换电影镜头，B 破墙，D 召唤巨龙，G 投石，H 隐藏界面，? 操作说明

## 文件

- index.html：游戏本体（单文件）
- 	hree.min.js：Three.js 0.160.1（MIT，见 THIRD-PARTY-NOTICES.md）
- og.jpg：分享预览图

## 部署

当前由 GitHub Pages 从 main 分支根目录发布（含 .nojekyll）。也可以把本目录整体上传到 Cloudflare Pages，无需构建命令，输出目录就是仓库根目录。

开发源码、验收记录与截图在开发目录 seek-kingdom/ 中，不在本仓库内。
