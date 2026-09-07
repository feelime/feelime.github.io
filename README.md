# feelime.github.io

Feelime 官网首页（https://feelime.github.io/ ）。

- 首页：`index.html`（单文件，含交互式键盘预览：真实键盘源码 + 模拟桥）
- 键盘源码快照：`kb-preview-src/`（VERSION / index.html / keyboard.css / keyboard.js）

## 同步键盘预览

键盘源码有更新时，从主仓库同步后提交：

```bash
cp ../feelime/app/src/main/assets/keyboard/{VERSION,index.html,keyboard.css,keyboard.js} kb-preview-src/
git commit -am "sync keyboard 3.x.y" && git push
```
