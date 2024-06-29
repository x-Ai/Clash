### 配置总规则
```
[custom]
;不要随意改变关键字，否则会导致出错
;acl4SSR规则

;去广告：支持
;自动测速：支持
;微软分流：支持
;苹果分流：支持
;增强中国IP段：支持
;增强国外GFW：支持

;设置规则标志位
;有个小技巧，下列不同列表可能会有重复规则，可以将想要命中的规则尽量提前
ruleset=🚀 节点选择,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/proxies.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/direct.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/LocalAreaNetwork.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/UnBan.list
ruleset=🛑 广告拦截,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanAD.list
ruleset=🍃 应用净化,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanProgramAD.list
ruleset=🆎 AdBlock,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanEasyList.list
ruleset=🆎 AdBlock,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanEasyListChina.list
ruleset=🆎 AdBlock,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/ad.list
ruleset=🛡️ 隐私防护,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanEasyPrivacy.list
ruleset=📢 谷歌FCM,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/GoogleFCM.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/GoogleCN.list
ruleset=Ⓜ️ 微软云盘,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/OneDrive.list
ruleset=Ⓜ️ 微软服务,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Microsoft.list
ruleset=🍎 苹果服务,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Apple.list
ruleset=📲 Telegram,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Telegram.list
ruleset=🎮 游戏平台,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Epic.list
ruleset=🎮 游戏平台,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Sony.list
ruleset=🎮 游戏平台,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Steam.list
ruleset=🎮 Nintendo,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/Nintendo.list
ruleset=🤖 OpenAI,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/openai.list
ruleset=🤖 DeepL,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/deepl.list
ruleset=🎵 TikTok,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/TikTok.list
ruleset=📹 YouTube,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/YouTube.list
ruleset=🎥 Netflix,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Netflix.list
ruleset=🎥 Netflix,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/NetflixIP.list
ruleset=🎥 Disney+,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/DisneyPlus.list
ruleset=📽️ PrimeVideo,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AmazonPrimeVideo/AmazonPrimeVideo.yaml
ruleset=🌪 Gitlab,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/Gitlab.list
ruleset=🎼 Spotify,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/spotify.list
ruleset=🍑 DMMCOJP,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/dmmjp.list
ruleset=📺 巴哈姆特,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Bahamut.list
ruleset=📺 Bilibili,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Bilibili.list
ruleset=📺 Bilibili,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/BilibiliHMT.list
ruleset=🌏 国内媒体,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaMedia.list
ruleset=🌍 国外媒体,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/ProxyMedia.list
ruleset=📰 微博,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/weibo.list
ruleset=💬 微信,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/wechat.list
ruleset=🍠 小红书,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/XiaoHongShu.list
ruleset=🕺 字节跳动,https://raw.githubusercontent.com/chinnsenn/ClashCustomRule/master/ByteDance.list
ruleset=🚀 节点选择,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyGFWlist.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaDomain.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ChinaCompanyIp.list
ruleset=🎯 全球直连,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Download.list
ruleset=🎯 全球直连,[]GEOIP,CN
ruleset=🐟 漏网之鱼,[]FINAL
;设置规则标志位

;设置分组标志位
custom_proxy_group=🚀 节点选择`select`[]♻️ 自动选择`[]🔯 故障转移`[]🚀 手动切换`[]DIRECT`[]🇸🇬 狮城节点-自动`[]🇭🇰 香港节点-自动`[]🇨🇳 台湾节点-自动`[]🇯🇵 日本节点-自动`[]🇺🇲 美国节点-自动`[]🇰🇷 韩国节点-自动`[]🇬🇧 英国节点`[]🇩🇪 德国节点`[]🇨🇦 加拿大节点`[]🇧🇷 巴西节点`[]🇮🇳 印度节点`[]🇱🇺 卢森堡节点`[]🇳🇱 荷兰节点`[]🇮🇹 意大利节点`[]🇨🇭 瑞士节点`[]🇫🇷 法国节点`[]🇸🇦 沙特阿拉伯节点`[]🇮🇱 以色列节点`[]🇦🇪 迪拜节点`[]🇲🇽 墨西哥节点`[]🇨🇱 智利节点`[]🇦🇷 阿根廷节点`[]🇿🇦 南非节点`[]🇸🇪 瑞典节点`[]🇹🇷 土耳其节点
custom_proxy_group=🚀 手动切换`select`.*
custom_proxy_group=♻️ 自动选择`url-test`(^(?!.*x(?:[2-9]|[1-9][0-9])))`http://www.gstatic.com/generate_204`300,100
custom_proxy_group=🔯 故障转移`fallback`.*`http://www.gstatic.com/generate_204`300,100
custom_proxy_group=🐟 漏网之鱼`select`[]DIRECT`[]🚀 节点选择`[]♻️ 自动选择`[]🇸🇬 狮城节点-自动`[]🇭🇰 香港节点-自动`[]🇨🇳 台湾节点-自动`[]🇯🇵 日本节点-自动`[]🇺🇲 美国节点-自动`[]🇰🇷 韩国节点-自动`[]🇬🇧 英国节点`[]🇩🇪 德国节点`[]🇨🇦 加拿大节点`[]🇧🇷 巴西节点`[]🇮🇳 印度节点`[]🇱🇺 卢森堡节点`[]🇳🇱 荷兰节点`[]🇮🇹 意大利节点`[]🇨🇭 瑞士节点`[]🇫🇷 法国节点`[]🇸🇦 沙特阿拉伯节点`[]🇮🇱 以色列节点`[]🇦🇪 迪拜节点`[]🇲🇽 墨西哥节点`[]🇨🇱 智利节点`[]🇦🇷 阿根廷节点`[]🇿🇦 南非节点`[]🇸🇪 瑞典节点`[]🇹🇷 土耳其节点`[]🇦🇺 澳大利亚节点`[]🇵🇰 巴基斯坦节点`[]🇹🇭 泰国节点`[]🇵🇭 菲律宾节点`[]🇷🇺 俄罗斯`[]🚀 手动切换
custom_proxy_group=📲 Telegram`select`[]🚀 节点选择`[]♻️ 自动选择`[]🇸🇬 狮城节点-自动`[]🇭🇰 香港节点-自动`[]🇨🇳 台湾节点-自动`[]🇯🇵 日本节点-自动`[]🇺🇲 美国节点-自动`[]🇰🇷 韩国节点-自动`[]🇬🇧 英国节点`[]🇩🇪 德国节点`[]🇨🇦 加拿大节点`[]🇧🇷 巴西节点`[]🇮🇳 印度节点`[]🇱🇺 卢森堡节点`[]🇳🇱 荷兰节点`[]🇮🇹 意大利节点`[]🇨🇭 瑞士节点`[]🇫🇷 法国节点`[]🇸🇦 沙特阿拉伯节点`[]🇮🇱 以色列节点`[]🇦🇪 迪拜节点`[]🇲🇽 墨西哥节点`[]🇨🇱 智利节点`[]🇦🇷 阿根廷节点`[]🇿🇦 南非节点`[]🇸🇪 瑞典节点`[]🇹🇷 土耳其节点`[]🇦🇺 澳大利亚节点`[]🇵🇰 巴基斯坦节点`[]🇹🇭 泰国节点`[]🇵🇭 菲律宾节点`[]🚀 手动切换
custom_proxy_group=📹 YouTube`select`[]🚀 节点选择`[]♻️ 自动选择`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇸🇬 狮城节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点-自动`[]🇬🇧 英国节点`[]🇩🇪 德国节点`[]🇨🇦 加拿大节点`[]🇧🇷 巴西节点`[]🇮🇳 印度节点`[]🇱🇺 卢森堡节点`[]🇳🇱 荷兰节点`[]🇮🇹 意大利节点`[]🇨🇭 瑞士节点`[]🇫🇷 法国节点`[]🇸🇦 沙特阿拉伯节点`[]🇮🇱 以色列节点`[]🇦🇪 迪拜节点`[]🇲🇽 墨西哥节点`[]🇨🇱 智利节点`[]🇦🇷 阿根廷节点`[]🇿🇦 南非节点`[]🇸🇪 瑞典节点`[]🇹🇷 土耳其节点`[]🇦🇺 澳大利亚节点`[]🚀 手动切换
custom_proxy_group=🎼 Spotify`select`[]🚀 节点选择`[]♻️ 自动选择`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇸🇬 狮城节点`[]🇺🇲 美国节点`[]🇰🇷 韩国节点-自动`[]🇬🇧 英国节点`[]🇩🇪 德国节点`[]🇨🇦 加拿大节点`[]🇧🇷 巴西节点`[]🇮🇳 印度节点`[]🇱🇺 卢森堡节点`[]🇳🇱 荷兰节点`[]🇮🇹 意大利节点`[]🇨🇭 瑞士节点`[]🇫🇷 法国节点`[]🇸🇦 沙特阿拉伯节点`[]🇮🇱 以色列节点`[]🇦🇪 迪拜节点`[]🇲🇽 墨西哥节点`[]🇨🇱 智利节点`[]🇦🇷 阿根廷节点`[]🇿🇦 南非节点`[]🇸🇪 瑞典节点`[]🇹🇷 土耳其节点`[]🇦🇺 澳大利亚节点`[]🚀 手动切换
custom_proxy_group=🤖 OpenAI`select`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇸🇬 狮城节点`[]🇺🇲 美国节点
custom_proxy_group=🤖 DeepL`select`.*`[]DIRECT
custom_proxy_group=🎵 TikTok`select`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇸🇬 狮城节点`[]🇺🇲 美国节点
custom_proxy_group=🎥 Netflix`select`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇸🇬 狮城节点`[]🇺🇲 美国节点`[]🇦🇺 澳大利亚节点
custom_proxy_group=🎥 Disney+`select`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇸🇬 狮城节点`[]🇺🇲 美国节点
custom_proxy_group=📽️ PrimeVideo`select`[]🇭🇰 香港节点`[]🇨🇳 台湾节点`[]🇯🇵 日本节点`[]🇸🇬 狮城节点`[]🇺🇲 美国节点
custom_proxy_group=🇭🇰 香港节点`select`(港|HK|Hong Kong)
custom_proxy_group=🇯🇵 日本节点`select`(日本|川日|东京|大阪|泉日|埼玉|沪日|深日|JP|Japan)
custom_proxy_group=🇺🇲 美国节点`select`(美|美国|波特兰|达拉斯|俄勒冈|凤凰城|费利蒙|硅谷|拉斯维加斯|洛杉矶|圣何塞|圣克拉拉|西雅图|芝加哥|United States|(?<![a-zA-Z])US(?![a-zA-Z])|(?<![a-zA-Z])USA(?![a-zA-Z])|(?<![a-zA-Z])USD(?![a-zA-Z]))
custom_proxy_group=🇨🇳 台湾节点`select`(台|新北|彰化|TW|Taiwan)
custom_proxy_group=🇸🇬 狮城节点`select`(新加坡|坡|狮城|SG|Singapore)
custom_proxy_group=🇰🇷 韩国节点`select`(KR|Korea|KOR|首尔|韩|韓)
custom_proxy_group=🇭🇰 香港节点-自动`url-test`(^(?!.*x(?:[2-9]|[1-9][0-9]))(?=.*(?:港|香港|HongKong|HK|Hong Kong)).*$)`http://www.gstatic.com/generate_204`300,100
custom_proxy_group=🇯🇵 日本节点-自动`url-test`(^(?!.*x(?:[2-9]|[1-9][0-9]))(?=.*(?:日本|川日|东京|大阪|泉日|埼玉|沪日|深日|JP|Japan)).*$)`http://www.gstatic.com/generate_204`300,100
custom_proxy_group=🇺🇲 美国节点-自动`url-test`(^(?!.*x(?:[2-9]|[1-9][0-9]))(?=.*(?:美|美国|波特兰|达拉斯|俄勒冈|凤凰城|费利蒙|硅谷|拉斯维加斯|洛杉矶|圣何塞|圣克拉拉|西雅图|芝加哥|United States|(?<![a-zA-Z])US(?![a-zA-Z])|(?<![a-zA-Z])USA(?![a-zA-Z])|(?<![a-zA-Z])USD(?![a-zA-Z]))).*$)`http://www.gstatic.com/generate_204`300,,150
custom_proxy_group=🇨🇳 台湾节点-自动`url-test`(^(?!.*x(?:[2-9]|[1-9][0-9]))(?=.*(?:台|新北|彰化|TW|Taiwan)).*$)`http://www.gstatic.com/generate_204`300,100
custom_proxy_group=🇸🇬 狮城节点-自动`url-test`(^(?!.*x(?:[2-9]|[1-9][0-9]))(?=.*(?:新加坡|坡|狮城|SG|Singapore)).*$)`http://www.gstatic.com/generate_204`300,100
custom_proxy_group=🇰🇷 韩国节点-自动`url-test`(^(?!.*x(?:[2-9]|[1-9][0-9]))(?=.*(?:KR|Korea|KOR|首尔|韩|韓))`http://www.gstatic.com/generate_204`300,100
custom_proxy_group=📺 巴哈姆特`select`[]🇨🇳 台湾节点-自动`[]🚀 节点选择`[]🚀 手动切换`[]DIRECT
custom_proxy_group=🍑 DMMCOJP`select`[]🇯🇵 日本节点
custom_proxy_group=📺 Bilibili`select`[]DIRECT`[]🎯 全球直连`[]🇨🇳 台湾节点-自动`[]🇭🇰 香港节点-自动
custom_proxy_group=🌪 Gitlab`select`[]DIRECT`[]🎯 全球直连`[]🇨🇳 台湾节点-自动`[]🇭🇰 香港节点-自动
custom_proxy_group=🌍 国外媒体`select`[]🚀 节点选择`[]♻️ 自动选择`[]🇭🇰 香港节点-自动`[]🇨🇳 台湾节点-自动`[]🇸🇬 狮城节点-自动`[]🇯🇵 日本节点-自动`[]🇺🇲 美国节点-自动`[]🇰🇷 韩国节点-自动`[]🚀 手动切换`[]DIRECT
custom_proxy_group=🌏 国内媒体`select`[]DIRECT`[]🇭🇰 香港节点-自动`[]🇨🇳 台湾节点-自动`[]🇸🇬 狮城节点-自动`[]🇯🇵 日本节点-自动`[]🚀 手动切换
custom_proxy_group=📢 谷歌FCM`select`[]🚀 节点选择`[]♻️ 自动选择`[]🇸🇬 狮城节点-自动`[]🇭🇰 香港节点-自动`[]🇨🇳 台湾节点-自动`[]🇯🇵 日本节点-自动`[]🇺🇲 美国节点-自动`[]🇰🇷 韩国节点-自动`[]🇬🇧 英国节点`[]🇩🇪 德国节点`[]🇨🇦 加拿大节点`[]🇧🇷 巴西节点`[]🇮🇳 印度节点`[]🇱🇺 卢森堡节点`[]🇳🇱 荷兰节点`[]🇮🇹 意大利节点`[]🇨🇭 瑞士节点`[]🇫🇷 法国节点`[]🇸🇦 沙特阿拉伯节点`[]🇮🇱 以色列节点`[]🇦🇪 迪拜节点`[]🇲🇽 墨西哥节点`[]🇨🇱 智利节点`[]🇦🇷 阿根廷节点`[]🇿🇦 南非节点`[]🇸🇪 瑞典节点`[]🇹🇷 土耳其节点`[]🇦🇺 澳大利亚节点`[]🇵🇰 巴基斯坦节点`[]🇹🇭 泰国节点`[]🇵🇭 菲律宾节点`[]🇷🇺 俄罗斯`[]🚀 手动切换
custom_proxy_group=Ⓜ️ 微软云盘`select`[]DIRECT`[]🚀 节点选择`[]♻️ 自动选择`[]🇸🇬 狮城节点-自动`[]🇭🇰 香港节点-自动`[]🇨🇳 台湾节点-自动`[]🇯🇵 日本节点-自动`[]🇺🇲 美国节点-自动`[]🇰🇷 韩国节点-自动`[]🇬🇧 英国节点`[]🇩🇪 德国节点`[]🇨🇦 加拿大节点`[]🇧🇷 巴西节点`[]🇮🇳 印度节点`[]🇱🇺 卢森堡节点`[]🇳🇱 荷兰节点`[]🇮🇹 意大利节点`[]🇨🇭 瑞士节点`[]🇫🇷 法国节点`[]🇸🇦 沙特阿拉伯节点`[]🇮🇱 以色列节点`[]🇦🇪 迪拜节点`[]🇲🇽 墨西哥节点`[]🇨🇱 智利节点`[]🇦🇷 阿根廷节点`[]🇿🇦 南非节点`[]🇸🇪 瑞典节点`[]🇹🇷 土耳其节点`[]🇦🇺 澳大利亚节点`[]🇵🇰 巴基斯坦节点`[]🇹🇭 泰国节点`[]🇵🇭 菲律宾节点`[]🇷🇺 俄罗斯`[]🚀 手动切换
custom_proxy_group=Ⓜ️ 微软服务`select`[]DIRECT`[]🚀 节点选择`[]♻️ 自动选择`[]🇸🇬 狮城节点-自动`[]🇭🇰 香港节点-自动`[]🇨🇳 台湾节点-自动`[]🇯🇵 日本节点-自动`[]🇺🇲 美国节点-自动`[]🇰🇷 韩国节点-自动`[]🇬🇧 英国节点`[]🇩🇪 德国节点`[]🇨🇦 加拿大节点`[]🇧🇷 巴西节点`[]🇮🇳 印度节点`[]🇱🇺 卢森堡节点`[]🇳🇱 荷兰节点`[]🇮🇹 意大利节点`[]🇨🇭 瑞士节点`[]🇫🇷 法国节点`[]🇸🇦 沙特阿拉伯节点`[]🇮🇱 以色列节点`[]🇦🇪 迪拜节点`[]🇲🇽 墨西哥节点`[]🇨🇱 智利节点`[]🇦🇷 阿根廷节点`[]🇿🇦 南非节点`[]🇸🇪 瑞典节点`[]🇹🇷 土耳其节点`[]🇦🇺 澳大利亚节点`[]🇵🇰 巴基斯坦节点`[]🇹🇭 泰国节点`[]🇵🇭 菲律宾节点`[]🇷🇺 俄罗斯`[]🚀 手动切换
custom_proxy_group=🍎 苹果服务`select`[]DIRECT`[]🚀 节点选择`[]♻️ 自动选择`[]🇸🇬 狮城节点-自动`[]🇭🇰 香港节点-自动`[]🇨🇳 台湾节点-自动`[]🇯🇵 日本节点-自动`[]🇺🇲 美国节点-自动`[]🇰🇷 韩国节点-自动`[]🇬🇧 英国节点`[]🇩🇪 德国节点`[]🇨🇦 加拿大节点`[]🇧🇷 巴西节点`[]🇮🇳 印度节点`[]🇱🇺 卢森堡节点`[]🇳🇱 荷兰节点`[]🇮🇹 意大利节点`[]🇨🇭 瑞士节点`[]🇫🇷 法国节点`[]🇸🇦 沙特阿拉伯节点`[]🇮🇱 以色列节点`[]🇦🇪 迪拜节点`[]🇲🇽 墨西哥节点`[]🇨🇱 智利节点`[]🇦🇷 阿根廷节点`[]🇿🇦 南非节点`[]🇸🇪 瑞典节点`[]🇹🇷 土耳其节点`[]🇦🇺 澳大利亚节点`[]🇵🇰 巴基斯坦节点`[]🇹🇭 泰国节点`[]🇵🇭 菲律宾节点`[]🇷🇺 俄罗斯`[]🚀 手动切换
custom_proxy_group=🎮 游戏平台`select`[]DIRECT`[]🚀 节点选择`[]♻️ 自动选择`[]🇸🇬 狮城节点-自动`[]🇭🇰 香港节点-自动`[]🇨🇳 台湾节点-自动`[]🇯🇵 日本节点-自动`[]🇺🇲 美国节点-自动`[]🇰🇷 韩国节点-自动`[]🇬🇧 英国节点`[]🇩🇪 德国节点`[]🇨🇦 加拿大节点`[]🇧🇷 巴西节点`[]🇮🇳 印度节点`[]🇱🇺 卢森堡节点`[]🇳🇱 荷兰节点`[]🇮🇹 意大利节点`[]🇨🇭 瑞士节点`[]🇫🇷 法国节点`[]🇸🇦 沙特阿拉伯节点`[]🇮🇱 以色列节点`[]🇦🇪 迪拜节点`[]🇲🇽 墨西哥节点`[]🇨🇱 智利节点`[]🇦🇷 阿根廷节点`[]🇿🇦 南非节点`[]🇸🇪 瑞典节点`[]🇹🇷 土耳其节点`[]🇦🇺 澳大利亚节点`[]🇵🇰 巴基斯坦节点`[]🇹🇭 泰国节点`[]🇵🇭 菲律宾节点`[]🇷🇺 俄罗斯`[]🚀 手动切换
custom_proxy_group=📰 微博`select`[]DIRECT`[]🚀 节点选择`[]♻️ 自动选择`[]🇸🇬 狮城节点-自动`[]🇭🇰 香港节点-自动`[]🇨🇳 台湾节点-自动`[]🇯🇵 日本节点-自动`[]🇺🇲 美国节点-自动`[]🇰🇷 韩国节点-自动`[]🇬🇧 英国节点`[]🇩🇪 德国节点`[]🇨🇦 加拿大节点`[]🇧🇷 巴西节点`[]🇮🇳 印度节点`[]🇱🇺 卢森堡节点`[]🇳🇱 荷兰节点`[]🇮🇹 意大利节点`[]🇨🇭 瑞士节点`[]🇫🇷 法国节点`[]🇸🇦 沙特阿拉伯节点`[]🇮🇱 以色列节点`[]🇦🇪 迪拜节点`[]🇲🇽 墨西哥节点`[]🇨🇱 智利节点`[]🇦🇷 阿根廷节点`[]🇿🇦 南非节点`[]🇸🇪 瑞典节点`[]🇹🇷 土耳其节点`[]🇦🇺 澳大利亚节点`[]🇵🇰 巴基斯坦节点`[]🇹🇭 泰国节点`[]🇵🇭 菲律宾节点`[]🇷🇺 俄罗斯`[]🚀 手动切换
custom_proxy_group=💬 微信`select`[]DIRECT`[]REJECT`[]🚀 手动切换
custom_proxy_group=🍠 小红书`select`[]DIRECT`[]REJECT`[]🚀 手动切换
custom_proxy_group=🕺 字节跳动`select`[]DIRECT`[]REJECT`[]🚀 手动切换
custom_proxy_group=🎮 Nintendo`select`[]🚀 节点选择`.*
custom_proxy_group=🎯 全球直连`select`[]DIRECT`[]🚀 节点选择`[]♻️ 自动选择
custom_proxy_group=🛑 广告拦截`select`[]REJECT`[]DIRECT
custom_proxy_group=🍃 应用净化`select`[]REJECT`[]DIRECT
custom_proxy_group=🆎 AdBlock`select`[]REJECT`[]DIRECT
custom_proxy_group=🛡️ 隐私防护`select`[]REJECT`[]DIRECT
custom_proxy_group=🇬🇧 英国节点`select`(UK|英|伦敦)
custom_proxy_group=🇩🇪 德国节点`select`(DE|德)
custom_proxy_group=🇨🇦 加拿大节点`select`(CA|Canada|加拿大|枫)
custom_proxy_group=🇧🇷 巴西节点`select`(BA|巴西)
custom_proxy_group=🇮🇳 印度节点`select`(IN|印度)
custom_proxy_group=🇱🇺 卢森堡节点`select`(LU|卢森堡)
custom_proxy_group=🇳🇱 荷兰节点`select`(NL|荷兰)
custom_proxy_group=🇮🇹 意大利节点`select`(IT|意大利|意)
custom_proxy_group=🇨🇭 瑞士节点`select`(CH|瑞士)
custom_proxy_group=🇫🇷 法国节点`select`(FR|法|巴黎)
custom_proxy_group=🇸🇦 沙特阿拉伯节点`select`(沙|沙特|阿拉伯)
custom_proxy_group=🇮🇱 以色列节点`select`(IL|以色列)
custom_proxy_group=🇦🇪 迪拜节点`select`(UAE|迪拜|杜拜|Dubayy)
custom_proxy_group=🇲🇽 墨西哥节点`select`(墨西哥|mexico|México|Mexican)
custom_proxy_group=🇨🇱 智利节点`select`(智利|Chile|CL)
custom_proxy_group=🇦🇷 阿根廷节点`select`(阿根廷|Argentina|AR)
custom_proxy_group=🇿🇦 南非节点`select`(南非|Zuid-Afrika)
custom_proxy_group=🇸🇪 瑞典节点`select`(瑞典|Sweden|Sverige)
custom_proxy_group=🇹🇷 土耳其节点`select`(TR|土耳其|土)
custom_proxy_group=🇦🇺 澳大利亚节点`select`(土澳|澳大利亚|澳|AUS)
custom_proxy_group=🇵🇭 菲律宾节点`select`(菲|PH)
custom_proxy_group=🇹🇭 泰国节点`select`(泰|TH)
custom_proxy_group=🇵🇰 巴基斯坦节点`select`(巴基斯坦|PK)
custom_proxy_group=🇷🇺 俄罗斯`select`(俄|俄罗斯|RUS|RF)
;设置分组标志位

enable_rule_generator=true
overwrite_original_rules=true
skip_failed_links=true

#过滤节点，正则匹配
exclude_remarks=(IPV6|重置|流量|用户|本站|漏洞|永久虚通路|车|邀|免翻|邀请|eevpn|域名|机场|刷新|禁止|备用登录|计划|面板|忘记|到期|套餐|官网|更多|关注|25倍率|http|增加|持续|渠道|购买|QQ|Ins|二手)

;luck
```

## 进阶配置

以下规则说明均摘自 [订阅转换规则](https://github.com/tindy2013/subconverter/blob/master/README-cn.md#%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6)

### ruleset

> 从本地或 url 获取规则片段
>
> 格式为 `Group name,[type:]URL[,interval]` 或 `Group name,[]Rule `
>
> 支持的type（类型）包括：surge, quanx, clash-domain, clash-ipcidr, clash-classic
>
> type留空时默认为surge类型的规则
>
> \[] 前缀后的文字将被当作规则，而不是链接或路径，主要包含 `[]GEOIP` 和 `[]MATCH`(等同于 `[]FINAL`)。

    -   例如：

    ```ini
    ruleset=🍎 苹果服务,https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Apple.list
    # 表示引用 https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Apple.list 规则
    # 且将此规则指向 [proxy_group] 所设置 🍎 苹果服务 策略组
    
    ruleset=Domestic Services,clash-domain:https://ruleset.dev/clash_domestic_services_domains,86400
    # 表示引用clash-domain类型的 https://ruleset.dev/clash_domestic_services_domains 规则
    # 规则更新间隔为86400秒
    # 且将此规则指向 [proxy_group] 所设置 Domestic Services 策略组
    
    ruleset=🎯 全球直连,rules/NobyDa/Surge/Download.list
    # 表示引用本地 rules/NobyDa/Surge/Download.list 规则
    # 且将此规则指向 [proxy_group] 所设置 🎯 全球直连 策略组
    
    ruleset=🎯 全球直连,[]GEOIP,CN
    # 表示引用 GEOIP 中关于中国的所有 IP
    # 且将此规则指向 [proxy_group] 所设置 🎯 全球直连 策略组
    
    ruleset=!!import:snippets/rulesets.txt
    # 表示引用本地的snippets/rulesets.txt规则
    ```

### custom_proxy_group

> 为 Clash 、Mellow 、Surge 以及 Surfboard 等程序创建策略组, 可用正则来筛选节点
>
> \[] 前缀后的文字将被当作引用策略组

```ini
custom_proxy_group=Group_Name`url-test|fallback|load-balance`Rule_1`Rule_2`...`test_url`interval[,timeout][,tolerance]
custom_proxy_group=Group_Name`select`Rule_1`Rule_2`...
# 格式示例
custom_proxy_group=🍎 苹果服务`url-test`(美国|US)`http://www.gstatic.com/generate_204`300,5,100
# 表示创建一个叫 🍎 苹果服务 的 url-test 策略组,并向其中添加名字含'美国','US'的节点，每隔300秒测试一次，测速超时为5s，切换节点的延迟容差为100ms
custom_proxy_group=🇯🇵 日本延迟最低`url-test`(日|JP)`http://www.gstatic.com/generate_204`300,5
# 表示创建一个叫 🇯🇵 日本延迟最低 的 url-test 策略组,并向其中添加名字含'日','JP'的节点，每隔300秒测试一次，测速超时为5s
custom_proxy_group=负载均衡`load-balance`.*`http://www.gstatic.com/generate_204`300,,100
# 表示创建一个叫 负载均衡 的 load-balance 策略组,并向其中添加所有的节点，每隔300秒测试一次，切换节点的延迟容差为100ms
custom_proxy_group=🇯🇵 JP`select`沪日`日本`[]🇯🇵 日本延迟最低
# 表示创建一个叫 🇯🇵 JP 的 select 策略组,并向其中**依次**添加名字含'沪日','日本'的节点，以及引用上述所创建的 🇯🇵 日本延迟最低 策略组
custom_proxy_group=节点选择`select`(^(?!.*(美国|日本)).*)
# 表示创建一个叫 节点选择 的 select 策略组,并向其中**依次**添加名字不包含'美国'或'日本'的节点
```

有了以上规则，理论上你可以自己配置所有你想要方式
