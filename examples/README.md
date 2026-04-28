# Examples

真实作品集。三个项目全部用 **apple-design-skill** 生成，覆盖 Mobile App / Web 官网两种场景。

## 1. HydroFlow — 运动水壶品牌 App

<p align="center">
  <img src="preview/hydroflow.png" alt="HydroFlow" width="320" />
</p>

- **设备**：Mobile 430×900
- **主题**：自然薄荷绿 `#00C896` + 奶白底
- **看点**：圆环饮水进度 / 7 天柱图 / 产品横滑 / 地球日 banner / 社区打卡
- **源码**：[`hydroflow-app/`](./hydroflow-app/)

---

## 2. PUFFY — 潮玩盲盒品牌 App

<p align="center">
  <img src="preview/puffy.png" alt="PUFFY" width="320" />
</p>

- **设备**：Mobile 430×900
- **主题**：奶油马卡龙（糖果粉 `#FF6BB5` + 蜜桃橙 + 薄荷 + 薰衣紫）
- **看点**：抓盒 sticker 风格 hero / IP 圆形头像 / 抽盒进度卡 / 收藏 6×2 格 / 欧气广场
- **源码**：[`puffy-app/`](./puffy-app/)

---

## 3. NOVA — 新势力电车品牌官网

<p align="center">
  <img src="preview/nova.png" alt="NOVA" width="860" />
</p>

- **设备**：Web Desktop 1440+ 响应式
- **主题**：暗色高级（电光青 `#00D4FF` + 深蓝 `#0066FF`）
- **看点**：全屏 Hero + 网格扫描线 + 青色光晕 / 三款车型对比 / 5 卡 Tech Grid / 数据条 / 5 列 Footer
- **源码**：[`nova-cars/`](./nova-cars/)
- **⚡ 配图亮点**：所有车型 / 内饰 / 技术特写由 AI（Gemini-3.0-Pro-Image）统一生成，品牌视觉 100% 一致

---

## 本地预览

```bash
# 1. clone
git clone https://github.com/dayviwong/apple-design-skill.git
cd apple-design-skill/examples

# 2. 任选一个项目开预览
open hydroflow-app/index.html
open puffy-app/index.html
open nova-cars/index.html
```

或者起一个本地静态 server 避免 `file://` 限制：

```bash
cd examples
python3 -m http.server 8080
# 浏览器打开 http://localhost:8080/hydroflow-app/
```

---

## 想生成类似的？

1. 按 [上层 README](../README.md) 安装 `apple-design-skill`
2. 跟 AI 说：
   - "做一个薄荷绿运动水壶 App 首页"
   - "做一个奶油色潮玩抽盒 App"
   - "做一个暗色科技感的新势力汽车官网"

AI 会自动按 Step 1A.2 调色板库 + Step 5.6 滚动架构 + Step 10.0 图片决策树生成。
