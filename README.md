# JJ-openclash-config

### 🔗 配置文件下载链接
**Step 1. 在Stash首页左上角，点击进入配置列表,导入-从URL下载，填写以下链接。**
**Original link:**
```text
https://raw.githubusercontent.com/sydneygao/JJ-openclash-config/main/JJ-openclash-config.yaml
```
**China acceleration 🚀:**
```text
https://cdn.jsdelivr.net/gh/sydneygao/JJ-openclash-config@main/JJ-openclash-config.yaml
```
**Step 2. 在Stash首页左上角，点击进入配置列表, 找到 `JJ-openclash-config.yaml`, 选择 "编辑", 填写机场订阅地址。**
```text
# 机场订阅
# 替换自己的机场订阅地址 url: "https://"
# 订阅更新频率(秒)，不更新填写 interval: 0
proxy-providers:
  Airport1:
    url: "https://"
    type: http
    interval: 86400
    health-check:
      enable: true
      url: https://www.gstatic.com/generate_204
      interval: 300
```
### 🤝 Contributing
Issues and Pull Requests are welcome to help improve this configuration!

