# JJ-openclash-config

### 🔗 配置文件下载链接
**主链路（gh-proxy.org｜缓存，≤60 秒更新）：**
```text
https://gh-proxy.org/https://raw.githubusercontent.com/sydneygao/JJ-openclash-config/main/JJ-config.yaml
```

**备用链路1（gh.idayer.com｜动态回源，实时更新）：**
```text
https://gh.idayer.com/https://raw.githubusercontent.com/sydneygao/JJ-openclash-config/main/JJ-config.yaml
```

**备用链路2（git.yylx.win｜动态回源，实时更新）：**
```text
https://git.yylx.win/https://raw.githubusercontent.com/sydneygao/JJ-openclash-config/main/JJ-config.yaml
```

**备用链路3（cdn.jsdelivr.net｜稳定，更新延迟12小时）：**
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

