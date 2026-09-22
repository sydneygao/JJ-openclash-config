# JJ-openclash-config

### 🔗 配置文件下载链接
**主链路（gh-proxy.org｜最快，≤60 秒更新）：**
```text
https://gh-proxy.org/https://raw.githubusercontent.com/sydneygao/JJ-openclash-config/main/JJ-config.yaml
```

**备链路（gh.idayer.com｜不同链路，实时）：**
```text
https://gh.idayer.com/https://raw.githubusercontent.com/sydneygao/JJ-openclash-config/main/JJ-config.yaml
```

**兜底链路（cdn.jsdelivr.net｜最稳，接受最长约 12 小时延迟）：**
```text
https://cdn.jsdelivr.net/gh/sydneygao/JJ-openclash-config@main/JJ-config.yaml
```

**编辑，添加机场订阅**
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

