直播本地使用：

https://raw.githubusercontent.com/880824/TV/main/live-local.m3u

https://mirror.ghproxy.com/https://raw.githubusercontent.com/880824/TV/main/live-local.m3u

Openwrt 上使用 Docker Pixman 4GTV 本地播放地址：

http://192.168.31.2:5000/4gtv.m3u

http://192.168.31.2:5000/ysp.m3u

Pixman Docker 地址：https://pixman.io/topics/17

例如youtube列表：https://www.youtube.com/playlist?list=PLbVAiNpblsKGf65bYnJtiaZpKEsSTyPzQ

则订阅链接就是：http://ip:port/youtube/list/PLbVAiNpblsKGf65bYnJtiaZpKEsSTyPzQ

即：http://192.168.31.2:5000/youtube/list/PLbVAiNpblsKGf65bYnJtiaZpKEsSTyPzQ

使用Cloudflare Worker代理免翻强观看YouTube视频：访问：自定义域名/live?url=油管链接 进行播放

例如：https://***.880824.xyz/live?url=https://www.youtube.com/watch?v=dmDg7NfUoSw
