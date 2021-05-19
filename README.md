# 脚本集合
CentOS7+ / Debian9+ / Ubuntu16.04+ 脚本集合

所有脚本源于网络，小柒只是汇聚脚本功能，方便大家使用而已！

目录

1.[VPS测试脚本](https://github.com/iam7cn/vps#VPS综合性能测试脚本（包含性能、速度、回程路由）)

2.[BBR 脚本](https://github.com/iam7cn/vps#BBR脚本)



# VPS综合性能测试脚本（包含性能、速度、回程路由）

脚本测速会大量消耗 VPS 流量，请悉知！

脚本运行代码：

``` 
wget -N --no-check-certificate https://raw.githubusercontent.com/iam7cn/vps/main/vpstest.sh && bash vpstest.sh 
```

# BBR脚本

## 原版BBR/魔改BBR/BBR Plus/锐速(Lotserver)四合一脚本/一键安装

```
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
```
原作者建议：不要随便在生产环境使用，生产环境建议手动安装
