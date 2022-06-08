## 自用Clash、Surge规则，依据热门规则整理

### DNS设置建议
现在的网站大多启用CDN，建议按所在地进行分流，国内DNS服务器解析国内地址，国外网站一律使用远程解析。

国内DNS推荐使用阿里、腾讯DOH，传统DNS仅用于解析DOH域名地址

223.5.5.5
114.114.114.114


```
# DNSpod
https://doh.pub/dns-query
```

```
# Aliyun
https://dns.alidns.com/dns-query
```
