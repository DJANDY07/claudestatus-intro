# ClaudeStatus 介绍页

ClaudeStatus 的动画介绍与演示页面：Claude Code 状态桌宠、按工具切换的动画、思考气泡、额度卡片、AFK 挂机、集群作业监督。

作者：**DJANDY07**

## 本地预览

直接双击 `index.html`，或者在本目录运行：

```bash
python -m http.server 8000
```

然后打开 http://localhost:8000 。

## 发布到 GitHub Pages

1. 在 GitHub 上新建一个空仓库（例如 `claudestatus`）。
2. 在本目录执行：

   ```bash
   git remote add origin https://github.com/<你的用户名>/claudestatus.git
   git push -u origin main
   ```

3. 仓库 **Settings → Pages**：Source 选 **Deploy from a branch**，分支选 `main`、目录选 `/ (root)`，保存。
4. 一两分钟后页面出现在 `https://<你的用户名>.github.io/claudestatus/`。

## 文件

- `index.html`：整个页面（样式和脚本都在里面，字体来自 Google Fonts）。
- `sprites/`：桌宠精灵条（192×256 像素网格，每帧横向排列）。

页面里的额度、集群作业等数字都是示例数据。桌宠渲染器与原始像素素材来自 state-interface（MIT）。社区项目，与 Anthropic 无关。
