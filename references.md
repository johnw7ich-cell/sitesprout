# SiteSprout 参考资料

## 2026-10-28 — 3D 网站特效动画库（YouTube Shorts，仅参考，未应用）

- 来源：Joh 2026-10-28 发来的参考链接
- 链接：https://youtube.com/shorts/dt5eT_MZ7tU
- 标题：《这才是Agent该用的3D网站特效动画库》
- 简介要点：做 3D 网站时，不要只让 AI“加一点高级感”，而是直接选现成特效，把提示词或源码交给 Agent。提到的方向包括粒子流场、玻璃反射、液态金属按钮；材质、光照和动画也可以一起给思路。
- 局限：页面文字只能拿到标题和简介，视频画面里的具体库名、提示词和源码链接未提取到，不能直接照搬那个库。
- 状态：仅存档，**没有改动 v2 网站**。Joh 2026-10-28 明确说“只是发我参考，先存起来”。

### 如果以后要应用，可对应的三处升级（未做，需 Joh 另行确认）

1. Hero 粒子：由现在的静态粒子改成流动的粒子流场。
2. 玻璃卡片：加强反射/折射感。
3. 主按钮：改成液态金属质感。

应用时不得改动已锁定的价格、业务规则、漏斗顺序和免责内容。

## 2026-10-28 — 设计灵感 / 特效网站与 Skill 完整表（Joh 截图整理，已核对链接）

说明：以下 20 项来自 Joh 2026-10-28 发来的两批截图（Vishnu.ai、Joaquin Fernandez、Alphenex、Lindsay.ai、Chase AI 视频截图），Realtime Colors 在两批中重复出现，只计一次。Alphenex 视频文案说有 3 个网站，但截图只显示了第 1、2 个，第 3 个未在截图中出现；Chase AI 视频中 GSAP Skills 标为 No.4，说明该视频前面还有未在截图中的项目。

| 分类 | 网站 / 工具 | 功能说明 | 链接 |
|---|---|---|---|
| 设计灵感图库 | Navbar Gallery | 按类型筛选的导航栏真站灵感：Static、Dropdown、Mega Menu、Side Bar、Search Bar 等 | https://www.navbar.gallery/style/design |
| 设计灵感图库 | Footer.design | 只做页脚的图库，按 Typographic、Grid、Animated、Cards 等风格/类型筛选 | https://footer.design/ |
| 设计灵感图库 | CTA.gallery | CTA 灵感图库：Button、Call-to-Buy、Download、Form、Modal / Pop-up、Navigation、Newsletter、Pricing / Subscription 等 | https://cta.gallery/ |
| 设计灵感图库 | Supahero | 精选真实网站 Hero 区（首屏）图库，现已并入 screensdesign | https://supahero.io/ |
| 设计灵感图库 | Godly | 手选 1000+ 网站灵感，带动态缩略图，可先预览动效再点进原站 | https://godly.design/ |
| AI 设计系统 / Agent 参考 | Refero Styles | 2000+ AI 可读设计系统：颜色、字体、间距、组件 + DESIGN.md，可用于 Cursor、Claude Code、Codex、v0、Lovable | https://styles.refero.design/ |
| AI 设计系统 / Agent 参考 | Inspo MCP | 832 个真实生产网站档案 + MCP：截图、调色、字体、组件、DESIGN.md，19 种版式结构，Agent 可直接查询 | https://inspomcp.dev/ |
| AI 设计系统 / Agent 参考 | Design Extract（designlang） | 一条命令提取任意网站完整设计系统：颜色、字体、间距、阴影、组件，输出 AI markdown、Tailwind、CSS 变量、React / shadcn 主题、Figma 变量、W3C tokens | https://github.com/Manavarya09/design-extract |
| 动效 / 交互组件 | Scrolltide | 滚动驱动模板、组件、Shader、区块的提示词库：复制提示词粘贴给 AI，含液态金属等 GPU 背景 | https://www.scrolltide.co/ |
| 动效 / 交互组件 | Bencho | 可实时把玩的 React 交互组件与微交互：Hover、Press、Drag、Slide、Swipe、Type、Select，含 Heat map 等 | https://bencho.dev/ |
| 动效 / 交互组件 | React Bits | 215+ 免费动画 React 组件与背景，可自己调参或交给 Agent，MIT + Commons Clause | https://github.com/DavidHDev/react-bits |
| 动效 / 交互组件 | GSAP Skills | GSAP 官方 AI Skill，教 Agent 用 Timeline、Tweens、ScrollTrigger、MotionPath、Flip，适用 Claude、Cursor、Copilot | https://github.com/greensock/gsap-skills |
| 3D / 玻璃 / 渐变 | react-three-fiber | 用 React 写 Three.js 的渲染器，JSX 即 3D 对象，是多数 3D 网站的底层 | https://github.com/pmndrs/react-three-fiber |
| 3D / 玻璃 / 渐变 | ShaderGradient | WebGL / Three.js 动画 3D 渐变背景：网站上可视化调颜色、形状、速度，URL 即配置，输出 React 代码 | https://github.com/ruucm/shadergradient |
| 3D / 玻璃 / 渐变 | liquid-glass-react | Web 液态玻璃 React 组件，可调 depth、transmission、reflectivity、roughness 等 | https://github.com/Specy/liquid-glass |
| 3D / 玻璃 / 渐变 | liquid-logo | 把透明 PNG Logo 变成液态金属动画，基于 Paper shaders，另有在线版 liquid.paper.design | https://github.com/paper-design/liquid-logo |
| 组件 / 素材 | Watermelon UI | 免费 MIT React 组件库（Tailwind + shadcn）：800+ 源码示例，动画组件、落地页区块、Dashboard、模板，shadcn CLI 安装 | https://ui.watermelon.sh/ |
| 组件 / 素材 | 3D Icons | 1500+ 手工 3D 图标渲染，CC0，开源免费 + 高级版，可在线改颜色角度，有 Figma 插件 | https://3dicons.co/ |
| 颜色字体 | Realtime Colors | 在真实网站上实时预览颜色 + 字体，导出 CSS / SCSS / Tailwind 等，含对比度检查，免费 | https://www.realtimecolors.com/ |
| AI 建站 Agent | Manus | 一句话生成带真实后端的应用 / 网站，无代码：前端、后端、数据库、登录、支付等由 Agent 完成 | https://manus.im/ |
