流光 (Flowing Light) 🍃

"风起于青萍之末，你的每一次抬头与回眸，都是风的方向。"

流光 是一款受陈星汉（Jenova Chen）设计哲学启发的禅意网页游戏。它不依赖键盘或鼠标，而是通过捕捉用户的头部运动来控制飞行的轨迹。

这款游戏的初衷是为了帮助久坐的上班族和开发者缓解颈椎僵硬。通过沉浸式的飞行体验、舒缓的视觉反馈和温柔的交互机制，引导用户在不知不觉中完成颈部拉伸与深呼吸练习。

✨ 核心特性 (Features)

🧘‍♀️ 颈部物理交互 (Neck-Controlled Gameplay)

基于 MediaPipe Face Mesh 技术，实时捕捉鼻尖位置。

无需任何穿戴设备，仅需普通电脑摄像头。

包含防抖算法 (Smoothing)，将头部运动转化为如丝般顺滑的飞行轨迹。

❤️ 爱与宽容机制 (Love & Forgiveness)

磁吸系统：不需要精准操作，只要你的意图靠近，光球就会主动飞向你。

光环奖励 (The Halo)：稀有的 Buff 赋予玩家巨大的吸附范围，象征着对他人的包容。

星尘收集：背景中的微小星尘皆可收集，给予全方位的正向反馈。

🎨 沉浸式视听体验

动态生成的星空与粒子系统。

随着能量积累而变化的拖尾色彩（金、青、紫、红）。

程序化生成的环境音效 (Web Audio API)，无需加载外部音频文件。

⏱️ 健康节奏设计

90秒旅程：每局游戏限制时长，避免过度疲劳。

呼吸冥想：游戏结束后强制进入“身心重置”阶段，通过视觉引导进行 12 秒的深呼吸放松。

🌍 双语支持

内置 中文 / English 一键切换。

🚀 快速开始 (Quick Start)

本地运行

由于游戏是 单文件 (Single-file) 架构，部署极其简单：

下载本项目中的 index.html 文件。

直接使用 Chrome、Edge 或 Safari 浏览器打开该文件。

点击页面上的 “允许摄像头” 授权。

根据引导，放松双肩，开始飞行。

注意：由于浏览器安全策略，摄像头权限通常要求 HTTPS 环境或 localhost。直接双击打开本地 HTML 文件可能在某些浏览器中无法启动摄像头。建议使用 VS Code 的 "Live Server" 插件或 Python 简单服务器 (python -m http.server) 运行。

🛠️ 技术栈 (Tech Stack)

核心语言: HTML5, Vanilla JavaScript (ES6+)

视觉渲染: HTML5 Canvas (2D Context), SVG, CSS3 Animations

计算机视觉: MediaPipe Face Mesh

样式库: Tailwind CSS (CDN)

音频: Web Audio API (Oscillators & GainNodes)

🔒 隐私说明 (Privacy Policy)

您的隐私绝对安全。

所有的面部识别与计算均在 您的浏览器本地 (Client-side) 完成。

视频流绝不会被上传到任何服务器。

游戏甚至可以在断网状态下运行（只要 CDN 缓存已加载）。

🎮 玩法指南

校准：保持坐姿舒适，脸部正对屏幕。

控制：

抬头 = 向上飞

低头 = 向下俯冲

转头 = 左右盘旋

目标：

收集 光球 (Orbs) 积累光辉。

寻找角落里的 旅人 (Travelers) 建立连结。

触发 光环 (Halo) 获得大范围磁吸能力。

📝 致谢与灵感

设计灵感来源于 陈星汉 (Jenova Chen) 的作品《Flower》与《Journey》。

📬 联系方式 (Contact)

如果您有任何建议、反馈或想分享您的体验，欢迎联系：
📧 Email: ycsy520@gmail.com

© 版权申明 (Copyright)

Copyright © 2024 Flowing Light. All Rights Reserved.
本项目代码开源，仅供学习与个人使用。未经允许，禁止用于商业盈利目的。

Made with ❤️ for a relaxed neck.
