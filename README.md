# GeoCN

每周更新中国大陆高精度IPV4+IPV6离线库，部分IP精确到区

下载地址：[GeoCN.mmdb](https://github.com/ljxi/GeoCN/releases/download/Latest/GeoCN.mmdb)

### Docker部署

docker run -d -p 127.0.0.1:8000:80 netart/ipapi

海外数据来着MaxMind，每天会自动拉取数据库



### 数据来源

1. 收集互联网上公开免费的高精度API
2. 扫描[MaxMind GeoLite2-City](https://github.com/P3TERX/GeoLite.mmdb)得到大陆地区IP段
3. 使用深度优先搜索算法获取IP数据
4. 整理IP数据，生成mmdb文件

### 性能

对于精确到区的数据接口，大约100万次请求即可遍历完所有数据

对于精确到市的数据接口，大约10万次请求即可遍历完所有数据

### 声明

本项目数据来源为公开免费的IP接口，如果本项目发布的数据中包含了您的商用数据，请与我联系！

