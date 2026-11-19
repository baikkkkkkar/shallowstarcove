# 星滩漫步｜阿默雾灯塔 UI 链接修正版

本次更新：

1. 已把你提供的第一张透明底灯塔图正式接入网页，统一命名为 `amo_lighthouse_ui.png`。
2. `xingtan_manbu.html` 的雾灯塔不再使用旧的 CSS 手绘灯塔 UI，改为直接引用透明底灯塔图层。
3. 星滩漫步主界面改为：默认停在「观海」，往左滑 / 按左箭头 / 按 A 键进入「00 雾灯塔」。
4. 观海卡片里删除了突兀的「前往雾灯塔」按钮，灯塔入口改成独立左滑章节。
5. `guanhai.html` 的灯塔热区继续引用同一个 `amo_lighthouse_ui.png`，保证两个页面看到的是同一座灯塔，不再割裂。
6. 已把你提供的第二张阿默灯塔章节插画接入 `amo_lighthouse.html`，统一命名为 `amo_lighthouse_scene.png`。
7. 保留真实星座科普互动：巨蟹座、猎户座、天琴座、天鹅座、天鹰座、天蝎座、大熊座、仙后座。

推荐文件结构：

- `xingtan_manbu.html`
- `guanhai.html`
- `amo_lighthouse.html`
- `amo_lighthouse_ui.png`
- `amo_lighthouse_scene.png`
- `bg-sea.jpg`
- `duck-idle.png`
- `duck-close.png`
- `duck-flap.png`
- `duck-kick.png`
- `duck-roll.png`
- `sea-waves.mp3`
- `ui-click.wav`
- `duck-quack.wav`
- `zhuye.html`（你自己的主页文件放同级即可）

更新说明：

这版重点是把雾灯塔 UI 做成和鸭鸭一样的独立 PNG 图层素材，并统一接到星滩漫步和观海页面中。
