# Clawd 桌宠示例（ii 手绘版）

由用户 `ii` 在像素画板中亲手逐格绘制的 Clawd 小螃蟹，转成悬浮窗 SVG 帧。

## 文件
- `pet.html` — 悬浮窗页面：透明背景 + 内联 SVG 帧 + CSS/JS 动画（浮动、点击蹦跳、气泡"咔咔！"）

## 使用方式
1. 把 `pet.html` 放到 `app/src/main/assets/` 目录
2. OverlayService 中加载：
   ```kotlin
   loadUrl("file:///android_asset/pet.html")
   ```
3. 按 README 第 179 条：`setBackgroundColor(0x00000000)` 必须在 `loadUrl` 之前调用

## 形象说明
- 像素矩阵：16×32（竖长条像素，每格 1×2）
- 主色：`#e6916a`（暖橙）
- 造型：方脑壳、两个黑眼洞、四条小短腿
- 作者手绘，未经修改，保留原样
