# KEVIN · 动作素材库 / Motion Clip Library

KEVIN 数字人的 18 段竖屏动作短片，覆盖对话应答、镜头签名、Hip-hop 舞蹈与系统待机状态。全部为 **1440 × 2560** 原生竖屏分辨率，单段 4.5 – 10.1 秒，总计约 60 MB。

> **在线浏览：** https://shawn-tkd.github.io/kevin-videos/ — 可直接在浏览器里逐条播放、下载。

---

## 素材清单

| # | 文件名 | 中文名 | English | 分类 | 时长 | 大小 |
|---|--------|--------|---------|------|------|------|
| 01 | `videos/01-proactive-question.mp4` | 主动提问 | Proactive Question | 对话与互动 | 4.5s | 1.2 MB |
| 02 | `videos/02-hiphop-dance.mp4` | Hip-hop 舞蹈 | Hip-hop Dance | 舞蹈表演 | 10.1s | 6.2 MB |
| 03 | `videos/03-kabedon-interaction.mp4` | 壁咚互动 | Kabedon Interaction | 对话与互动 | 8.0s | 5.7 MB |
| 04 | `videos/04-idle-interaction.mp4` | 待机互动 | Idle Interaction | 对话与互动 | 4.5s | 1.3 MB |
| 05 | `videos/05-idle-dance.mp4` | 待机舞蹈 | Idle Dance | 舞蹈表演 | 6.6s | 2.4 MB |
| 06 | `videos/06-fallback.mp4` | 兜底 | Fallback State | 系统状态 | 6.6s | 2.0 MB |
| 07 | `videos/07-black-vest-hiphop-dance.mp4` | 黑背心 Hip-hop 舞蹈 | Black Vest Hip-hop Dance | 舞蹈表演 | 10.0s | 9.1 MB |
| 08 | `videos/08-black-vest-camera-signature.mp4` | 黑背心镜头签名 | Black Vest Camera Signature | 镜头与签名 | 8.0s | 5.7 MB |
| 09 | `videos/09-camera-signature.mp4` | 镜头签名 | Camera Signature | 镜头与签名 | 8.0s | 5.7 MB |
| 10 | `videos/10-opening.mp4` | 开场 | Opening | 系统状态 | 4.5s | 1.2 MB |
| 11 | `videos/11-listening.mp4` | 倾听 | Listening | 对话与互动 | 4.5s | 1.2 MB |
| 12 | `videos/12-closing.mp4` | 收场 | Closing | 系统状态 | 4.5s | 1.2 MB |
| 13 | `videos/13-speaking.mp4` | 说话 | Speaking | 对话与互动 | 6.6s | 2.0 MB |
| 14 | `videos/14-thinking.mp4` | 思考 | Thinking | 对话与互动 | 4.5s | 1.2 MB |
| 15 | `videos/15-shirt-lift-interaction.mp4` | 掀衣互动 | Shirt-lift Interaction | 对话与互动 | 8.0s | 4.2 MB |
| 16 | `videos/16-suspended-mic-rap.mp4` | 悬吊麦克风说唱 | Suspended Mic Rap | 舞蹈表演 | 10.1s | 5.4 MB |
| 17 | `videos/17-beckoning.mp4` | 招揽 | Beckoning | 对话与互动 | 6.6s | 1.9 MB |
| 18 | `videos/18-asking-writing-permission.mp4` | 征求写作许可 | Asking Writing Permission | 对话与互动 | 6.6s | 1.8 MB |

---

## 分类速查

**对话与互动（9 段）** — 主动提问、倾听、说话、思考、招揽、征求写作许可、壁咚互动、掀衣互动、待机互动

**镜头与签名（2 段）** — 镜头签名、黑背心镜头签名

**舞蹈表演（4 段）** — Hip-hop 舞蹈、黑背心 Hip-hop 舞蹈、待机舞蹈、悬吊麦克风说唱

**系统状态（3 段）** — 开场、兜底、收场

---

## 使用方式

**1. 克隆整个仓库**

```bash
git clone https://github.com/Shawn-TKD/kevin-videos.git
```

**2. 单条直链下载**

把下面地址中的文件名替换成清单里的任意一条即可：

```
https://github.com/Shawn-TKD/kevin-videos/raw/main/videos/09-camera-signature.mp4
```

**3. 网页/前端嵌入**

```html
<video src="videos/13-speaking.mp4" controls playsinline
       poster="" width="360"></video>
```

竖屏 9:16 比例，建议容器宽 320–480px；配 `object-fit: cover` 可铺满卡片。

---

## 目录结构

```
kevin-videos/
├── index.html          # 在线播放页（GitHub Pages 首页）
├── README.md
└── videos/
    ├── 01-proactive-question.mp4
    ├── ...
    └── 18-asking-writing-permission.mp4
```

---

## 说明

- 文件名统一使用英文 slug，便于 CDN、网页直链与跨平台引用；中文名称保留在本清单与网页界面中。
- 全部素材为公开素材，可自由下载、分发与二次剪辑。
