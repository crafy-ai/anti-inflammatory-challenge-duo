# 抗炎挑战（双人版）

一个适合两人共同使用的抗炎饮食打卡网页。项目为单文件静态应用，可直接在浏览器中运行。

## 功能

- 双人打卡与进度记录
- 抗炎饮食挑战任务
- 浏览器本地数据存储
- 可选的腾讯云开发 CloudBase 数据同步
- 移动端响应式界面

## 在线访问

GitHub Pages：

https://crafy-ai.github.io/anti-inflammatory-challenge-duo/

## 本地使用

直接用浏览器打开 `index.html`，或者在项目目录启动静态服务器：

```bash
python -m http.server 8000
```

随后访问 `http://localhost:8000/`。

## 云端同步

页面默认可以在本地使用。若需要两台设备同步数据，可在页面中按照提示创建腾讯云开发 CloudBase 环境，并填写自己的环境 ID。

仓库中不包含任何 CloudBase 环境 ID、访问密钥或个人账号信息。

## License

[MIT License](LICENSE)
