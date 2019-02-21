# BGP-IPLocation
基于BGP获取的IP库，准确度远比其他免费离线库高~

## 如何使用

### 下载库
```
git clone https://github.com/cuteSakuraHime/BGP-IPLocation.git
```

### iproute2

```
ip route add (CIDR文件中的IP) dev Device via Gateway
```

## 说明

GCE不在本库精准标注范围内，因为GCE是乱播的，得人工统计。