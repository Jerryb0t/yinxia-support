# 隐匣支持页面

这是《隐匣》的 GitHub Pages 静态支持页面包。

当前目录包含：

- `index.html`：隐匣支持页面
- `privacy.html`：隐匣隐私政策页面
- `README.md`：上传与发布说明

## 发布方式

这个目录用于之后单独上传到 GitHub 仓库 `yinxia-support` 的根目录。

建议步骤：

1. 在 GitHub 创建仓库：`yinxia-support`。
2. 将 `Website/` 里的三个文件上传到 `yinxia-support` 仓库根目录：
   - `index.html`
   - `privacy.html`
   - `README.md`
3. 打开仓库的 `Settings`。
4. 进入 `Pages`。
5. 在 `Build and deployment` 中选择 `Deploy from a branch`。
6. Branch 选择 `main`。
7. Folder 选择 `/ (root)`。
8. 保存后等待 GitHub Pages 部署完成。

部署完成后，页面通常会发布到：

```text
https://<你的 GitHub 用户名>.github.io/yinxia-support/
```

隐私政策页面通常会是：

```text
https://<你的 GitHub 用户名>.github.io/yinxia-support/privacy.html
```

## 发布前需要替换的占位内容

- `[待填写支持邮箱]`
- 如后续已有 App Store 链接，可在 `index.html` 中补充
- 如隐私政策内容发生变化，需要同步更新 `privacy.html`

## 约束

这些页面是纯静态 HTML/CSS：

- 不加载第三方 CDN
- 不加载外部脚本
- 不使用统计、广告或追踪
- 不使用外部字体
- 不将 VoiceOver / 旁白验收标记为已完成
- 不使用过度安全承诺

## 当前状态说明

当前 App 基线：

- 最新提交：`ac88617 fix: polish stage 6 simulator layout issues`
- 阶段 6 可提交修复已收口
- MVP 不标记完成

仍保留为真机或稳定模拟器补测项：

- VoiceOver / 旁白基础验收
- 真机 Face ID / 设备口令链路
- 后台锁定与隐私遮罩
- 最大字号主流程可达性
