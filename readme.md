This is my first LaTeX cv

PS:在Github被墙的情况下，一直push不了，而在使用Lantern后依然不行，在线搜索解决方案http://www.laoliu-soft.net/183/

$ git config --global http.proxy http://127.0.0.1:8787

$ git config --global https.proxy http://127.0.0.1:8787

输入后依然没能解决问题

尝试端口1091也不行

在蓝灯设置界面点击“设置”-“高级设置”-勾选“代理全部流量”显示：

HTTP(S)代理服务器：127.0.0.1:1092

SOCKS代理服务器：127.0.0.1:1094

再次尝试端口1092，成功

遂正确的解决方案如下

$ git config --global http.proxy http://127.0.0.1:1092

$ git config --global https.proxy http://127.0.0.1:1092

