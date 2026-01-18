RetroFX - 创意图片处理器 🎨

RetroFX 是一个基于 Web 技术的轻量级图片处理工具，专注于提供独特的艺术风格和复古滤镜。

无需上传图片到服务器，所有处理均在本地浏览器通过 HTML5 Canvas 高效完成，保护用户隐私。

✨ 主要功能

核心特性

纯前端处理：利用 Canvas API，离线可用，速度快，隐私安全。

20MB 大图支持：优化的算法支持处理高分辨率图片。

实时对比：支持“长按对比”和“滑动对比轴”两种模式。

裁剪与旋转：内置九宫格裁剪和基础旋转工具。

🖼️ 滤镜库

我们拥有丰富的创意滤镜，支持参数自定义：

经典复古：

📺 老电视 (Old TV)：模拟 CRT 扫描线、色差和噪点。

🎞️ 胶片暗角 (Vignette)：电影感的边缘压暗效果。

📜 旧海报 (Poster)：双色调阈值化风格。

☕ 怀旧 (Sepia) & 🌑 黑白 (Grayscale)。

艺术风格：

🖋️ EVA 终章 (One Last)：复刻经典的《One Last Kiss》专辑封面素描风格 (Color Dodge 算法)。

🎨 油画 (Oil Paint)：模拟梵高式的块状笔触。

🖌️ 水墨 (Ink Wash)：中国风黑白晕染效果。

🖍️ 蜡笔 (Crayon)：粗糙的颗粒感和童趣色彩。

🏙️ 赛博朋克 (Cyberpunk)：高强度的双色调霓虹映射。

特殊效果：

👾 像素风 (Pixel Art)：降低分辨率并进行色彩量化。

⚡ 故障风 (Glitch)：模拟数字信号损坏的视觉错乱。

🧱 浮雕 (Emboss)：提取纹理细节。

🌫️ 马赛克 (Mosaic)：支持全图或局部选区打码。

🛠️ 技术栈

核心：原生 HTML5, JavaScript (Canvas API)

样式：Tailwind CSS (通过 CDN 引入)

图标：FontAwesome (通过 CDN 引入)

🚀 如何使用 (GitHub Codespaces)

本项目已配置 Dev Container，可直接在 GitHub Codespaces 中运行：

点击仓库绿色的 Code 按钮，选择 Codespaces 标签页，点击 Create codespace on main。

等待环境构建完成（会自动安装 Live Server 插件）。

在 VS Code 编辑器底部状态栏，点击 Go Live 按钮。

浏览器将自动弹出预览窗口，即可开始使用。

📦 本地运行

直接双击打开 index.html 即可使用，或者使用任意静态服务器（如 python -m http.server）。

📝 待办事项 / 维护计划

[ ] 添加更多自定义滤镜（如波普艺术风格）。

[ ] 优化移动端触摸体验。

[ ] 增加图片批量处理功能。

[ ] 引入 WebGL 加速以处理更大尺寸图片。

Created with Gemini# retro-image-studio
