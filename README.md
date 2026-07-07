<h1 align="center">
  <br>
  <img src="https://img.shields.io/badge/🐍-NEON%20SNAKE-ff2e63?style=for-the-badge&logo=windowsterminal&logoColor=white" alt="NEON SNAKE">
  <br>
  贪吃蛇 · 霓虹赛博
  <br>
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Web_Audio_API-ff2e63?style=flat-square&logo=webrtc&logoColor=white" alt="Web Audio">
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="License">
</p>

<p align="center">
  <strong>🎮 一款赛博朋克风格的经典贪吃蛇游戏 — 霓虹灯效 · 激昂电音 · 技能 Buff · 粒子特效</strong>
</p>

<p align="center">
  <a href="#-游戏特色">🎯 特色</a> •
  <a href="#-操作指南">🎮 操作</a> •
  <a href="#-玩法说明">📖 玩法</a> •
  <a href="#-道具体系">💎 道具</a> •
  <a href="#-音效系统">🎵 音效</a> •
  <a href="#-快速开始">🚀 开始</a> •
  <a href="#-项目结构">📁 结构</a>
</p>

---

## 🎯 游戏特色

<table>
  <tr>
    <td width="50%">
      <h3>🎨 霓虹赛博视觉</h3>
      <ul>
        <li>渐变霓虹色蛇身，每条蛇节独立色彩</li>
        <li>动态星空背景 + 网格线</li>
        <li>玻璃态毛玻璃 UI 面板</li>
        <li>粒子爆炸特效（吃食物 / 触发护盾）</li>
        <li>浮动文字提示（Buff 激活 / 护盾触发）</li>
        <li>护盾环绕光环动画</li>
      </ul>
    </td>
    <td width="50%">
      <h3>🎵 激昂电子音乐</h3>
      <ul>
        <li><strong>Web Audio API 程序化生成</strong> — 无需任何外部音频文件</li>
        <li>四轨电子配乐：底鼓 · 军鼓 · 踩镲 · 贝斯 · 主旋律</li>
        <li>138 BPM 高能节奏，赛博朋克风格</li>
        <li>吃食物音效 — 清脆的 "叮咚" 双音</li>
        <li>吃 Buff 音效 — 四连升调琶音</li>
        <li>通关/失败独立配乐反馈</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>⚡ 丰富道具体系</h3>
      <ul>
        <li>🔥 <strong>加速</strong> — 移速翻倍，持续 5 秒</li>
        <li>💜 <strong>减速</strong> — 移速减半，持续 5 秒</li>
        <li>🟠 <strong>穿墙</strong> — 穿越边界，持续 8 秒</li>
        <li>🔵 <strong>护盾</strong> — 抵挡一次致命碰撞，持续 6 秒</li>
        <li>🟢 <strong>双倍成长</strong> — 吃食物长度翻倍增长，持续 6 秒</li>
      </ul>
    </td>
    <td width="50%">
      <h3>🕹️ 便捷操控</h3>
      <ul>
        <li>⏯️ <strong>暂停/继续</strong> — 点击按钮或按 <kbd>Esc</kbd></li>
        <li>🔄 <strong>立即重玩</strong> — 点击按钮或按 <kbd>R</kbd>（随时可用）</li>
        <li>🎵 <strong>音乐开关</strong> — 点击按钮或按 <kbd>M</kbd></li>
        <li>⌨️ 支持 <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> 和 <kbd>↑</kbd><kbd>←</kbd><kbd>↓</kbd><kbd>→</kbd> 双套键位</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🎮 操作指南

### ⌨️ 键盘操作

| 按键 | 功能 |
|:---:|:---|
| <kbd>W</kbd> / <kbd>↑</kbd> | 向上移动 |
| <kbd>S</kbd> / <kbd>↓</kbd> | 向下移动 |
| <kbd>A</kbd> / <kbd>←</kbd> | 向左移动 |
| <kbd>D</kbd> / <kbd>→</kbd> | 向右移动 |
| <kbd>Space</kbd> | 开始游戏 / 暂停切换 |
| <kbd>Esc</kbd> | **暂停 / 继续** |
| <kbd>R</kbd> | **立即重玩**（任何时间可用） |
| <kbd>M</kbd> | **音乐开关**（任何时间可用） |

### 🖱️ 鼠标操作

| 按钮 | 功能 |
|:---:|:---|
| **⏯️ 暂停** | 暂停或继续游戏 |
| **🔄 重玩** | 立即重新开始 |
| **🎵 音乐** | 切换背景音乐开关 |

---

## 📖 玩法说明

### 🎯 游戏目标
操控贪吃蛇**吃掉场上所有黄色食物方块**即可通关获胜！

### 📜 规则
1. **初始状态**：蛇长度为 1，场上随机生成 15~35 个食物方块
2. **每吃一个食物**：蛇身 +1 长度（双倍 Buff 下 +2）
3. **胜利条件**：吃掉所有食物 → 🎉 通关！
4. **失败条件**：撞到墙壁或自己的身体 → 💀 游戏结束
5. **随机的乐趣**：每局食物数量和位置随机生成，每局体验都不同

### 🎲 难度曲线
- 食物数量在 **15 ~ 35 个**之间随机
- 蛇越长，避障难度越大
- Buff 道具会随机替换场上的食物，收集它们来获得优势

---

## 💎 道具体系

游戏中有 **5 种 Buff 道具**，吃食物时有概率在食物位置生成：

<table>
  <tr>
    <th>图标</th>
    <th>名称</th>
    <th>颜色</th>
    <th>持续时间</th>
    <th>效果</th>
  </tr>
  <tr>
    <td>🔥</td>
    <td><strong>加速</strong></td>
    <td><code>#ff2e63</code> 红</td>
    <td>5 秒</td>
    <td>移动速度翻倍，反应要快！</td>
  </tr>
  <tr>
    <td>💜</td>
    <td><strong>减速</strong></td>
    <td><code>#7c4dff</code> 紫</td>
    <td>5 秒</td>
    <td>移动速度减半，更容易精确控制</td>
  </tr>
  <tr>
    <td>🟠</td>
    <td><strong>穿墙</strong></td>
    <td><code>#ffa500</code> 橙</td>
    <td>8 秒</td>
    <td>穿越边界从另一侧出现，不会死亡</td>
  </tr>
  <tr>
    <td>🔵</td>
    <td><strong>护盾</strong></td>
    <td><code>#00e5ff</code> 蓝</td>
    <td>6 秒</td>
    <td>抵挡一次致命碰撞（撞墙或撞自己），触发后护盾消失</td>
  </tr>
  <tr>
    <td>🟢</td>
    <td><strong>双倍成长</strong></td>
    <td><code>#00ff00</code> 绿</td>
    <td>6 秒</td>
    <td>每次吃食物蛇身长度翻倍增长（+2 而非 +1）</td>
  </tr>
</table>

> 💡 **提示**：Buff 效果可以叠加！例如同时拥有「加速」和「双倍」可以快速刷分。当前激活的 Buff 会显示在游戏上方的状态栏中，并附带剩余时间倒计时。

---

## 🎵 音效系统

本游戏使用 **Web Audio API** 程序化生成所有音效，无需下载任何音频文件，打开即玩！

### 🎼 背景音乐（138 BPM 电子乐）

| 音轨 | 乐器 | 描述 |
|:---:|:---:|:---|
| 🥁 Kick | 正弦波低频 | 四拍底鼓，持续驱动节奏 |
| 🥁 Snare | 白噪声 + 三角波 | 二四拍军鼓，增加律动感 |
| 🥁 Hi-hat | 高通白噪声 | 八分音符踩镲，保持速度感 |
| 🎸 Bass | 低频锯齿波 | 低音贝斯线，G-F-C-A# 走向 |
| 🎹 Lead | 方波主旋律 | 旋律线，E4-G4-A4-D4 音高 |

### 🔊 游戏音效

| 音效 | 触发条件 | 音频特征 |
|:---:|:---|:---|
| 🍎 **吃食物** | 蛇头碰到食物 | 双正弦波 "叮咚" 升调 — 520→880Hz |
| 💎 **吃 Buff** | 蛇头碰到 Buff 道具 | 四连方波升调琶音 — 渐强的力量感 |
| 🛡️ **护盾触发** | 护盾抵挡致命伤害 | 三角波急速升频 — 200→1200Hz |
| 💀 **游戏结束** | 撞墙/撞自己 | 锯齿波下行 — 440→80Hz 悲伤滑音 |
| 🎉 **通关** | 吃完所有食物 | 四音方波琶音 C5-E5-G5-C6 胜利号角 |

### 🎚️ 音量控制
- 背景音乐默认开启，音量适中（不会盖过音效）
- 暂停时音乐自动降低音量
- 游戏结束/通关时音乐自动降低音量
- 点击 **🎵 音乐** 按钮或按 <kbd>M</kbd> 键可随时开关

---

## 🚀 快速开始

### 方式一：直接打开（推荐）

```bash
# 克隆仓库
git clone https://github.com/wasabi553/snake-game.git
# 或
git clone https://gitcode.com/2301_80788168/snake-game.git

# 用浏览器直接打开
open snake.html
```

> 🎯 **双击 `snake.html` 即可开始游戏！** 无需安装任何依赖。

### 方式二：本地服务器

```bash
# 使用 Python
python -m http.server 8080

# 使用 Node.js
npx serve .

# 浏览器打开
# http://localhost:8080/snake.html
```

### 🌐 在线体验

访问以下任一平台即可在线游玩：

- **GitHub Pages**: [https://wasabi553.github.io/snake-game](https://wasabi553.github.io/snake-game)
- **GitCode Pages**: [https://2301_80788168.gitcode.io/snake-game](https://2301_80788168.gitcode.io/snake-game)

---

## 📁 项目结构

```
snake-game/
├── snake.html          # 🎮 游戏主文件（HTML + CSS + JS 全部内嵌）
├── README.md           # 📖 项目文档
└── .gitignore          # 🔧 Git 忽略配置
```

> 📝 **单文件架构**：整个游戏只有一个 `snake.html` 文件，包含所有 HTML 结构、CSS 样式和 JavaScript 游戏逻辑。零依赖、零构建步骤、即开即玩。

---

## 🔧 技术亮点

| 技术 | 应用 |
|:---|:---|
| **Canvas 2D** | 游戏画面渲染，包括蛇身渐变、粒子系统、护盾光环 |
| **Web Audio API** | 程序化音乐生成（无需音频文件），多音轨实时合成 |
| **requestAnimationFrame** | 60fps 流畅渲染循环 |
| **CSS Glassmorphism** | 毛玻璃 UI 面板、霓虹发光效果 |
| **CSS Animations** | Buff 状态脉冲动画、暂停文字呼吸效果 |
| **响应式布局** | 自适应不同屏幕尺寸（clamp / vw / vh） |

### 🎹 音频架构

```
AudioContext
  ├── musicGain (背景音乐总线，音量 0.22)
  │   ├── Kick    → 正弦波 150→40Hz 快速衰减
  │   ├── Snare   → 白噪声包络 + 三角波鼓腔
  │   ├── Hi-hat  → 高通白噪声短促爆发
  │   ├── Bass    → 锯齿波 lowpass 滤波
  │   └── Lead    → 方波 lowpass 滤波旋律
  │
  └── sfxGain (音效总线，音量 0.6)
      ├── Eat     → 双正弦波升调
      ├── Buff    → 四连方波琶音
      ├── Shield  → 三角波升频扫描
      ├── GameOver→ 锯齿波下行滑音
      └── Win     → 四音方波胜利琶音
```

---

## 🎯 游戏截图

```
┌──────────────────────────────────────────┐
│         🐍 贪吃蛇 · NEON SNAKE            │
│  ┌──────────┐  ┌──────────┐              │
│  │ 长度   5  │  │ 剩余  22 │              │
│  └──────────┘  └──────────┘              │
│  [⏯️暂停] [🔄重玩] [🎵音乐]               │
│  [🔥 加速 3s] [🔵 护盾 5s]               │
│  ┌──────────────────────────┐            │
│  │  · · · · · · · · · · · │            │
│  │  ·  🟡  ·  ·  🟡  ·  · │            │
│  │  ·  ·  ·  🔴  ·  ·  · │            │
│  │  ·  🟡  · 🔴 ·  🟡 ·  · │            │
│  │  ·  ·  · 🔴 ·  ·  · · │            │
│  │  ·  ·  ·  ·  ·  ·  🟡 │            │
│  │  ·  💎  ·  ·  ·  ·  · │            │
│  └──────────────────────────┘            │
│  移动：W A S D | 暂停：Esc | 重玩：R      │
└──────────────────────────────────────────┘
```

---

## 📄 License

MIT © 2025

---

<p align="center">
  <sub>Made with ❤️ and lots of 🎵 Web Audio API magic</sub>
</p>
