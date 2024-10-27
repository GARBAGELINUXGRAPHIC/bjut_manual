# bjut_manual

北京工业大学 / 北工大 / BJUT 生活指南，包含一键免流上网等提高QOL的项目

### 欢迎commit

## 免流上网

详见<a href="https://quitsense.cn:8443">https://quitsense.cn:8443</a>

尝试的项目：

[x] 登录账号并使用ipv6免流（可用）

[x] 不登录账号时使用 53 端口（不可用，TCP、UDP均可获取DNS信息，但是无法curl到信息或连接到SS服务器，因此网关会验证发包是否为DNS请求）

[x] 67、68端口（不可用，无法连接到SS服务器）

[ ] 80端口+http伪装为lgn.bjut.edu.cn（暂时没有试过，主要原因是80端口转发服务器太贵了，还不如直接给学校冲套餐）

## WebVPN访问主页之外的地址（如EDUOJ内网OJ系统）

访问<a href="https://wpn.citrons.cc/">https://wpn.citrons.cc/</a>选中北京工业大学，输入内网网址并转换即可直接在浏览器访问。

例如eduOJ转换后就是<a href="https://webvpn.bjut.edu.cn/http/77726476706e69737468656265737421a1a013d2756126012946d8fccc/home">https://webvpn.bjut.edu.cn/http/77726476706e69737468656265737421a1a013d2756126012946d8fccc/home</a>
