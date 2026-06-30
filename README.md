# GetNote x YiXiaoEr Board

苹果橙色简洁看板，用来查看 Get 笔记、知识库，并把选中的笔记改写成公众号、小红书和口播文案。

## 长期入口

GitHub Pages:

https://yanruwill-dot.github.io/getnote-yixiaoer-board/

## 运行边界

- GitHub Pages 只托管前端页面，不保存 GetNote / Hermes / 蚁小二密钥。
- 真实笔记数据仍通过本机桥 `http://127.0.0.1:8796` 读取。
- 本机桥只允许本机页面和 `https://yanruwill-dot.github.io` 调用。
- 远程页面不允许调用保存草稿接口，避免误触发平台发布副作用。

## 本机桥

在本机启动：

```bash
cd /Users/will/Desktop/00-AI资料/getnote-yixiaoer-board
npm start
```

