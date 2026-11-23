# 🌼 口袋山谷 · Pocket Valley

[![Play on GitHub Pages](https://img.shields.io/badge/Play%20Online-GitHub%20Pages-6aa86e?style=for-the-badge&logo=github)](https://linxianying.github.io/pocket-valley/)

一款柔和绘本水彩风模拟经营农场小游戏，打开浏览器即可直接游玩，支持**四季天气、荷花池垂钓、农场萌宠、阳光牧场、小屋厨房烹饪**，以及**中/英文切换、移动端触屏手柄、PWA 离线安装与 Google Drive 云存档同步**。

A cozy storybook watercolor farming, fishing, ranching, and cooking game playable directly in the browser — featuring **4 seasons & dynamic weather, lotus pond fishing, farm pets, a sunny pasture, cottage cooking, bilingual ZH/EN UI, mobile touch controls, offline PWA support, and Google Drive cloud save**.

👉 **立即在线游玩 / Play Online**: https://linxianying.github.io/pocket-valley/

---

## ✨ 特色玩法 / Features

- **🎨 开局定制农庄与角色 / Custom Character, Cottage & Map Layout**
  - 新开局即可自由选择**男孩 / 女孩**角色与 **4 套对应田园穿搭**（女孩 4 款碎花裙；男孩背带装、田园衫、森系马甲、暖织开衫）。
  - 可选 **4 种田园小屋样式**（红瓦奶油小屋、森林绿瓦木屋、薰衣草童话屋、蜂蜜茅草农舍）与 **3 种农庄地图布局**（荷花东池「水池靠右」、荷花西池「水池靠左」、溪畔双田「水池居中」），支持实时预览；角色与小屋外观在游玩中也可随时通过顶部「👗 换装」修改。
- **🏡 田园农庄 / Home Farm**
  - 开垦农田、种植 **10 种农作物**（芜菁、小麦、樱桃萝卜、胡萝卜、小番茄、甜玉米、草莓、蓝莓、南瓜、杨桃），其中小番茄、甜玉米、草莓、蓝莓支持成熟后重复收获。
  - 可升级**锄头**与**浇水壶**，使用**镰刀**清理杂草，并摆放**自动洒水器**与夜晚发光的**田园提灯**。
- **🌸 四季轮转与动态天气 / Seasons & Dynamic Weather**
  - **春夏秋冬四季**（每季 14 天），每个季节都有对应的应季加成作物、水彩配色与氛围粒子（花瓣、夏夜萤火虫、秋日枫叶、冬日飞雪）。
  - **5 种天气**（晴天、多云、微风、细雨、雪天）与明日天气预报；细雨天会自动浇灌农田，并配有清晨→白昼→黄昏→夜晚的渐变光影。
- **🎣 荷花池垂钓与图鉴 / Lotus Pond Fishing & Fish Dex**
  - 在荷花池畔甩杆钓鱼，体验轻松的拉杆蓄力小游戏，收集 **6 种水产**（河鲈、小龙虾、锦鲤、彩虹鳟鱼、月光水母、黄金鲤鱼），部分鱼类仅在特定天气、季节或夜晚（19:00 后）出没，并记录最大重量。
- **🐾 农场萌宠伙伴 / Farm Pet Companions**
  - 领养**三花猫**、**柯基犬**或**垂耳兔**，陪你一起逛农庄和牧场，随时互动抚摸。
- **🐮 阳光牧场 / Sunny Pasture**
  - 向东穿过花园木门（或点击顶部「去牧场」按钮）即可前往牧场，饲养 **4 种动物**（小母鸡、小白鸭、软绵羊、花奶牛），喂食牧草并抚摸提升好感，每天清晨收获鸡蛋、鸭蛋、羊毛与鲜牛奶。
- **🍳 小屋厨房与 12 道料理 / Cottage Kitchen & 12 Recipes**
  - 升级厨房后，用收获的农作物、牧场鲜产、垂钓鱼获与杂货食材烹饪 **12 道料理**（田园鲜蔬沙拉、太阳嫩煎蛋卷、蜂蜜黄油吐司、奶油胡萝卜炖菜、番茄玉米浓汤、草莓奶油小蛋糕、蓝莓酥皮派、焦糖鸭蛋布丁、黄金南瓜浓汤、香煎香草鱼排、海鲜浓汤、星光水果塔）。
- **💾 实时双备份存档与 Google 云同步 / Local Backup & Google Cloud Sync**
  - 游戏操作后 1 秒内自动保存到浏览器本地（`localStorage` + `IndexedDB` 双重备份），支持 JSON 文件导出与导入。
  - 可在存档面板中配置自己的 Google OAuth Client ID，将存档私密同步至个人 Google Drive 应用数据空间（`appDataFolder`），跨设备无缝续玩。
- **📱 移动端适配与 PWA 离线游玩 / Mobile & Offline PWA**
  - 支持点击地图自动寻路交互、可切换的虚拟方向键手柄（`🕹️`）及钓鱼专属拉杆按钮。
  - 内置 `manifest.json` 与 Service Worker（`sw.js`），支持添加到手机主屏幕或桌面，离线也能游玩。
- **🌐 中英双语 / Bilingual UI**
  - 顶部一键切换 `中文 / EN`，内置可开关的 Web Audio 轻快音效。

---

## 🎮 操作说明 / Controls

### 电脑端 / Desktop

| 按键 / 操作 | 功能说明 / Action |
| --- | --- |
| `WASD` / `方向键` / 点击地图 | 移动与自动寻路互动 / Walk & click-to-walk |
| `左键点击` / `Space` | 使用当前工具（耕地、浇水、播种、甩杆、钓鱼按住拉杆） |
| `E` / `右键点击` | 智能互动（采摘、收蛋挤奶、抚摸动物/宠物、进屋/开店、鱼咬钩提竿） |
| `1`–`9`, `0` / 鼠标滚轮 | 切换工具栏与种子 / Switch tools & seeds |
| `B` | 打开花种铺 / 牧场铺 / Open Farm or Ranch Shop |
| `C` | 打开小屋厨房 / Open Kitchen |
| `F` | 打开钓鱼图鉴 / Open Fish Dex |
| `I` / `Tab` | 打开花篮背包 / Open Satchel |
| `M` | 开关音效 / Toggle Sound |
| `Esc` | 关闭弹窗或取消钓鱼 / Close modal or cancel fishing |

### 手机与平板 / Mobile & Touch

- 点击地图任意位置即可自动走过去并执行耕种或互动。
- 点击顶部 `🕹️` 可随时显示或隐藏屏幕下方虚拟手柄与「使用工具 / 互动」按钮。
- 钓鱼时按住屏幕或专属「按住拉杆」按钮控制绿条收线。

---

## ☁️ 开启 Google 云存档（可选）/ Optional Google Cloud Sync

如需跨设备同步进度，可在游戏顶部点击 **💾 存档**，填入你自己在 [Google Cloud Console](https://console.cloud.google.com/) 创建的 **OAuth 2.0 Web Client ID**：

1. 在 Google Cloud Console 启用 **Google Drive API**。
2. 创建 Web 应用类型的 OAuth 2.0 客户端 ID，并将你的站点域名（例如 `https://linxianying.github.io`）加入 **Authorized JavaScript origins**。
3. 在游戏存档弹窗中填入 Client ID 并登录 Google 账号即可上传、恢复或开启自动云同步（仅访问私密 `drive.appdata` 空间，不会读取你 Drive 中的其他文件）。

---

## 📁 项目结构 / Project Structure

```text
pocket-valley/
├── index.html      # 完整单页游戏应用（HTML5 Canvas、音效、存档与云同步）
├── manifest.json   # PWA 应用清单
├── sw.js           # 离线缓存 Service Worker
├── icon.svg        # 矢量应用图标
├── icon-192.png    # PWA 192×192 图标
├── icon-512.png    # PWA 512×512 图标
└── README.md       # 项目说明文档
```

## 🚀 本地运行 / Play Locally

- 直接在现代浏览器中打开 `index.html` 即可开始游玩（无需构建步骤）。
- 如需体验 **PWA 离线缓存** 或 **Google 云同步**，建议通过本地静态服务器或 GitHub Pages（HTTPS）访问：

```bash
python3 -m http.server 8000
# 然后在浏览器访问 http://localhost:8000
```
