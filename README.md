# GeoCN

每周更新中国大陆高精度IP离线库，部分IP精确到区

下载地址：[Github](https://github.com/ljxi/GeoCN/releases/download/Latest/GeoCN.mmdb) [jsDelivr](https://cdn.jsdelivr.net/gh/ljxi/GeoCN@releases/download/Latest/GeoCN.mmdb)

### 数据来源

1. 收集互联网上公开免费的高精度API
2. 扫描MaxMind GeoLite2-City得到大陆地区IP段
3. 使用深度优先搜索算法获取IP数据
4. 整理IP数据，生成mmdb文件

### 性能

对于精确到区的数据接口，大约100万次请求即可遍历完所有数据
对于精确到市的数据接口，大约10万次请求即可遍历完所有数据

### 声明

本项目数据来源为公开免费的IP接口，如果本项目发布的数据中包含了您的商用数据，请与我联系！



