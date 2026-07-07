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
  <strong>🎮 赛博朋克风格经典贪吃蛇 — 霓虹光效 · 电子音乐 · 5种道具 · 粒子特效 · 纯前端零依赖</strong>
</p>

<p align="center">
  <a href="#-游戏特色">🎯 特色</a> •
  <a href="#-操作指南">🎮 操作</a> •
  <a href="#-玩法说明">📖 玩法</a> •
  <a href="#-道具体系">💎 道具</a> •
  <a href="#-音效系统">🎵 音效</a> •
  <a href="#-快速开始">🚀 开始</a> •
  <a href="#-技术架构">🔧 技术</a>
</p>

---

## 🎯 游戏特色

<table>
  <tr>
    <td width="50%">
      <h3>🎨 赛博朋克视觉</h3>
      <ul>
        <li>🌌 <strong>动态渐变背景</strong> — 三层径向光晕 + 网格纹理 + 12秒呼吸动画</li>
        <li>🪟 <strong>玻璃态毛玻璃面板</strong> — backdrop-filter 模糊 + 微光边框</li>
        <li>✨ <strong>标题流光动画</strong> — 渐变背景位移动画 (titleShimmer)</li>
        <li>🌈 <strong>游戏边框霓虹旋转光晕</strong> — conic-gradient 360°旋转</li>
        <li>🐍 <strong>渐变蛇身</strong> — 蛇头强辉光 + 身体 HSL 渐变色带</li>
        <li>⭐ <strong>闪烁星空背景</strong> — 亮星辉光 + 暗星闪烁</li>
        <li>🍎 <strong>食物内高光</strong> — 外发光 + 线性渐变模拟立体感</li>
        <li>💥 <strong>粒子径向爆炸</strong> — 吃食物/触发护盾时粒子散射</li>
        <li>🛡️ <strong>护盾双环特效</strong> — 实线内环 + 虚线旋转外环</li>
        <li>📊 <strong>数据卡片</strong> — 顶部高光线装饰</li>
      </ul>
    </td>
    <td width="50%">
      <h3>🎵 程序化电子音乐</h3>
      <ul>
        <li>🎼 <strong>五轨电子配乐</strong> — Kick · Snare · Hi-hat · Bass · Lead</li>
        <li>⚡ <strong>138 BPM 高能节奏</strong></li>
        <li>🔊 <strong>全部 Web Audio API 合成</strong> — 零外部音频文件</li>
        <li>🍎 吃食物 — 双正弦波 "叮咚" 520→880Hz</li>
        <li>💎 吃道具 — 四连方波升调琶音</li>
        <li>🛡️ 护盾触发 — 三角波急速扫频 200→1200Hz</li>
        <li>💀 失败 — 锯齿波下行滑音 440→80Hz</li>
        <li>🎉 通关 — C5-E5-G5-C6 四音胜利号角</li>
        <li>🎚️ 暂停/结束时自动降低音量</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>⚡ 5 种技能道具</h3>
      <ul>
        <li>🔥 <strong>加速</strong> — 移速翻倍，5秒 | 红色脉冲光</li>
        <li>💜 <strong>减速</strong> — 移速减半，5秒 | 紫色脉冲光</li>
        <li>🟠 <strong>穿墙</strong> — 穿越边界，8秒 | 橙色脉冲光</li>
        <li>🔵 <strong>护盾</strong> — 抵挡一次致命伤害（墙/自撞均可），6秒 | 蓝色双环旋转</li>
        <li>🟢 <strong>双倍成长</strong> — 吃食物长度+2，6秒 | 绿色脉冲光</li>
      </ul>
      <p><em>道具随机替换食物生成 · 效果可叠加 · 状态栏实时倒计时 · 暂停时计时冻结</em></p>
    </td>
    <td width="50%">
      <h3>🕹️ 完善操控</h3>
      <ul>
        <li>⏯️ <strong>暂停/继续</strong> — 按钮 或 <kbd>Esc</kbd> · Buff计时同步冻结</li>
        <li>🔄 <strong>立即重玩</strong> — 按钮 或 <kbd>R</kbd> · 任何时刻可用</li>
        <li>🎵 <strong>音乐开关</strong> — 按钮 或 <kbd>M</kbd></li>
        <li>⌨️ <strong>双套键位</strong> — WASD + 方向键 均支持</li>
        <li>🚀 <strong>空格键</strong> — 快速开始 / 暂停切换</li>
        <li>📱 <strong>响应式布局</strong> — 自适应手机/平板/桌面</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🎮 操作指南

### ⌨️ 键盘

| 按键 | 功能 |
|:---:|:---|
| <kbd>W</kbd> / <kbd>↑</kbd> | 向上移动 |
| <kbd>S</kbd> / <kbd>↓</kbd> | 向下移动 |
| <kbd>A</kbd> / <kbd>←</kbd> | 向左移动 |
| <kbd>D</kbd> / <kbd>→</kbd> | 向右移动 |
| <kbd>Space</kbd> | 开始游戏 / 暂停切换 |
| <kbd>Esc</kbd> | **暂停 / 继续**（Buff 计时同步冻结） |
| <kbd>R</kbd> | **立即重玩**（任何时间可用） |
| <kbd>M</kbd> | **音乐开关** |

### 🖱️ 鼠标

| 按钮 | 功能 |
|:---:|:---|
| ⏯️ **暂停** | 暂停 / 继续游戏 |
| 🔄 **重玩** | 立即重新开始本局 |
| 🎵 **音乐** | 切换背景音乐 / 静音 |

---

## 📖 玩法说明

### 🎯 目标
操控贪吃蛇**吃掉场上所有黄色食物方块**即可通关获胜！

### 📜 规则

| 项目 | 说明 |
|:---|:---|
| 初始状态 | 蛇长 1，场上随机 15~35 个食物 |
| 吃食物 | 蛇身 +1（双倍 Buff 下 +2） |
| 胜利 | 吃掉所有食物 → 🏆 通关 |
| 失败 | 撞边界 / 撞自己 → 💥 游戏结束 |
| 随机性 | 每局食物数量、位置、道具刷新均随机 |

### 🎯 失败提示

游戏会精确告诉你失败原因：
- 🧱 **"撞到边界了"** — 蛇头碰到墙壁
- 🐍 **"撞到自己了"** — 蛇头碰到身体
- 🛡️ **"穿墙后撞到了自己的身体"** — 护盾穿墙后落地撞到自己

---

## 💎 道具体系

场上食物有概率被替换为 **Buff 道具**，吃到即刻生效：

<table>
  <tr>
    <th>道具</th>
    <th>名称</th>
    <th>持续</th>
    <th>效果</th>
    <th>策略</th>
  </tr>
  <tr>
    <td>🔥</td>
    <td><strong>加速</strong></td>
    <td>5s</td>
    <td>移动速度 ×2</td>
    <td>快速清场，但操作难度加大</td>
  </tr>
  <tr>
    <td>💜</td>
    <td><strong>减速</strong></td>
    <td>5s</td>
    <td>移动速度 ÷2</td>
    <td>精确走位，适合蛇长时使用</td>
  </tr>
  <tr>
    <td>🟠</td>
    <td><strong>穿墙</strong></td>
    <td>8s</td>
    <td>穿越边界从对面出现</td>
    <td>无视地图边界，自由穿梭</td>
  </tr>
  <tr>
    <td>🔵</td>
    <td><strong>护盾</strong></td>
    <td>6s</td>
    <td>抵挡一次致命伤害<br><sub>（撞墙或撞自己均生效）</sub></td>
    <td>救命稻草，触发后护盾消失</td>
  </tr>
  <tr>
    <td>🟢</td>
    <td><strong>双倍成长</strong></td>
    <td>6s</td>
    <td>吃食物长度 +2</td>
    <td>搭配加速快速刷分</td>
  </tr>
</table>

> 💡 **提示**：Buff 可叠加！例如"加速"+"双倍"=快速刷分。"穿墙"+"护盾"=双重保险。暂停时所有 Buff 计时**冻结**，恢复后继续倒数。

---

## 🎵 音效系统

**零外部依赖** — 所有音频由 Web Audio API 实时合成。

### 🎼 背景音乐 — 138 BPM 电子乐

```
🎹 音轨架构：

Kick   ████████░░░░░░░░  ████████░░░░░░░░  — 正弦波 150→40Hz
Snare  ░░░░████░░░░░░░░  ░░░░████░░░░░░░░  — 白噪声+三角波
Hi-hat ██░░██░░██░░██░░  ██░░██░░██░░██░░  — 高通白噪声
Bass   ████░░░░░░██░░░░  ████░░░░░░░░██░░  — 锯齿波 G-F-C-A#
Lead   ░░░░░░██░░██░░░░  ░░██░░░░██░░░░██  — 方波 E4-G4-A4-D4
```

### 🔊 音效一览

| 事件 | 波形 | 频率 | 听感 |
|:---|:---|:---|:---|
| 🍎 吃食物 | 双正弦波 | 520→880Hz | 清脆叮咚 |
| 💎 吃道具 | 四连方波 | 300→900Hz 升调 | 力量渐强 |
| 🛡️ 护盾触发 | 三角波扫频 | 200→1200Hz | 能量爆发 |
| 💀 失败 | 锯齿波滑音 | 440→80Hz | 悲伤下行 |
| 🎉 通关 | 四音方波 | C5-E5-G5-C6 | 胜利号角 |

---

## 🚀 快速开始

### 方式一：直接打开（推荐）

```bash
git clone https://github.com/wasabi553/snake-game.git
# 或
git clone https://gitcode.com/2301_80788168/snake-game.git

# 双击 snake.html 即可！
```

> 🎯 **零依赖、零构建** — 浏览器打开即玩。

### 方式二：本地服务器

```bash
python -m http.server 8080
# 访问 http://localhost:8080/snake.html
```

---

## 🔧 技术架构

```
snake-game/
├── snake.html          # 🎮 单文件：HTML + CSS + JS 全部内嵌
├── README.md           # 📖 本文档
└── .gitignore
```

### 技术栈

| 层 | 技术 | 用途 |
|:---|:---|:---|
| 🎨 视觉 | CSS Glassmorphism + Animations | 毛玻璃面板、霓虹光晕、流光动画 |
| 🖼️ 渲染 | Canvas 2D | 蛇身渐变、粒子系统、护盾光环、星空 |
| 🔊 音频 | Web Audio API | 五轨音序器 + 五种音效实时合成 |
| 🎮 逻辑 | Vanilla JavaScript | 游戏状态机、碰撞检测、Buff系统 |
| 📐 布局 | Flexbox + clamp/vw/vh | 全响应式，手机到桌面自适应 |
| ⏱️ 计时 | performance.now() + setTimeout | 精确暂停/恢复，累计偏移算法 |

### 🧠 核心设计

**Buff 暂停机制**：采用累计暂停时长偏移算法，暂停时记录 `pausedAtTime`，恢复时累加到 `totalPausedDuration`，所有时间计算统一减去偏移量，确保暂停期间 Buff 倒计时完全冻结。

**音频音序器**：基于 `AudioContext.currentTime` 的 look-ahead 调度，每 40ms 检查并提前 150ms 排程音符，保证节奏稳定。

---

## 📄 License

MIT © 2025

---

<p align="center">
  <sub>Built with ❤️ · 🎵 Web Audio API · 🎨 CSS Art · 🎮 Canvas Magic</sub>
</p>
