# 🌈 CMTI (Chiang Mai Type Indicator)

<p align="center">
  <img src="images/cmi-logo.png" alt="CMI Community" width="100">
</p>

<p align="center">
  <strong>MBTI已经过时，SBTI已经过气，CMTI来了。<br>你是清迈社区的哪种生物？25种人格，总有一款是你！</strong>
</p>

<p align="center">
  🔗 <strong>线上测试入口：<a href="http://cmti.uk/">cmti.uk</a></strong>
</p>

---

## 🎨 关于项目

CMTI（Chiang Mai Type Indicator）是 **CMI 清迈数字游民社区** 出品的一款趣味人格测试工具。我们观察并提炼了清迈数字游民/在地华人的生活切片，总结出了 25 种各具特色的“社区生物”。

通过 30 道精心设计的场景测试题，从 15 个维度进行打分计算，最终会为你匹配最符合你的 CMTI 代号。

![CMTI 海报](images/cmti-poster.png)

## 🦄 25 种清迈人格

无论你是刚落地的新手，还是混迹多年的老炮，总能在里面找到自己的影子：

| | | | | |
| :--: | :--: | :--: | :--: | :--: |
| **ET**<br>倔行者 | **LUCKY**<br>暖场王 | **MILAN**<br>米兰 | **SQUIRREL**<br>反差怪 | **404**<br>社区幽灵 |
| **GU-GU**<br>咕咕帝 | **MIHUA**<br>米花 | **WIFI**<br>标准游民 | **CTRL+Z**<br>撤回者 | **CHEF**<br>厨神 |
| **RIDE**<br>骑士 | **MAX**<br>玩商王 | **GYM**<br>体校生 | **STAR**<br>交际花 | **JET-LAG**<br>时差人 |
| **ALIAS**<br>代号 | **POKER**<br>牌手 | **IMPRO**<br>即兴者 | **HIDE**<br>消失术 | **DUMP**<br>饺子王 |
| **SD**<br>山东人 | **ZEN**<br>灵修者 | **SOON**<br>下月走 | **OWL**<br>夜行者 | **VLOG**<br>打卡仙 |

## 🛠️ 技术实现

作为一个轻量级的 Web 互动应用，CMTI 具有以下特点：
- **纯前端架构**：采用 HTML5 + CSS3 + 原生 JavaScript（Vanilla JS）构建，无冗余框架依赖。
- **响应式排版**：全面适配移动端和桌面端网页展现。
- **离线卡片生成**：通过 HTML5 `<canvas>` API 在客户端本地实时合成精美的测试结果分享图片，兼顾响应速度和分享便捷性。
- **多渠道分享**：一键保存为本地图像，并针对微信及小红书应用场景提供专门的发布引导。

## 💡 开发与部署

项目采用纯静态资源结构：

```bash
git clone https://github.com/skyrim0624/cmti.git
```
直接双击打开 `index.html` 即可在本地进行预览测试。

线上由 GitHub Actions 联动 Netlify/Cloudflare 进行自动化托管，访问地址：[http://cmti.uk/](http://cmti.uk/)

## 🤝 贡献与反馈

如果你有更有趣的题目建议、设计脑洞，或者在清迈发现了更稀有的“新物种”，欢迎给我们提 Issue！社区生态由你共建。

---
<p align="center">
  <small>Made with 💛 by <strong>CMI Community</strong></small>
</p>
