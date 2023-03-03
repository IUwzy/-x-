# -x-
圈x
去广告
分流
规则
解锁网易云音乐
# 分流作用：修正某些被分流到外面的国内网站
# 重要提示：无
# 项目地址：https://raw.githubusercontent.com/fmz200/wool_scripts/main/QuantumultX/filter/fenliuxiuzheng.list
# 交流群组：https://t.me/quguanggao
# 更新时间：2023.02.15 17:10
# 策略选择：直连 direct
#############################################
# > "reject"        策略返回 HTTP 状态码 404,不附带任何额外内容
# > "reject-200"    策略返回 HTTP 状态码 200,不附带任何额外内容
# > "reject-img"    策略返回 HTTP 状态码 200,同时附带 1px gif
# > "reject-dict"   策略返回 HTTP 状态码 200,同时附带一个空的 JSON 对象
# > "reject-array"  策略返回 HTTP 状态码 200,同时附带一个空的 JSON 数组
#############################################


# > 苹果推送服务
host-keyword, push.apple.com, direct
# > 苹果时间同步
host, time.apple.com, direct
# > 苹果天气服务
host-keyword, weather-edge.apple.com, direct
host-keyword, weather-adge.apple.com, direct
host-suffix, weather-data.apple.com, direct
host-suffix, weather-map.apple.com, direct
host-suffix, weather-analytics-events.apple.com, direct
# > 苹果内购服务
host-keyword, buy.itunes.apple.com, direct
# > 苹果icloud
host-keyword, icloud.com, direct
# > 苹果输入法相关服务
host-keyword, api.smoot.apple.com, direct
host-keyword, api.smoot.apple.cn, direct
# > 苹果iMessage服务
host, init.ess.apple.com, direct
# > 苹果其他服务
host-keyword, ssl.apple.com, direct
host-keyword, humb.apple.com, direct
host, smp-device-content.apple.com, direct
host-keyword, api-adservices.apple.com, direct
host-keyword, ls.apple.com, direct
host-keyword, gsa.apple.com, direct
host-keyword, ess.apple.com, direct

# > QQ空间
host-keyword, ctc.qzs.qzone.qq.com, direct

# > 路由器后台
ip-cidr, 192.168.0.1/24, direct
# > 天翼网关
ip-cidr, 192.168.1.1/24, direct

# > 其他分流修正
host-keyword, anti-ad.net, direct

host, ad.12306.cn, direct
