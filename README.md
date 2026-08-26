# JJ-openclash-config
## OpenClash Configuration File for OpenWrt Systems.

### 🔗 Configuration Download Links
### In OpenClash's "Config Management", select "Upload":

**Original link:**
```text
https://raw.githubusercontent.com/sydneygao/JJ-openclash-config/main/JJ-openclash-config.yaml
```
**China acceleration 🚀:**
```text
https://cdn.jsdelivr.net/gh/sydneygao/JJ-openclash-config@main/JJ-openclash-config.yaml
```
**In the configuration file list, find `JJ-openclash-config.yaml`, select "Edit", fill in the complete ✈️airport subscription address, save and apply.**
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

