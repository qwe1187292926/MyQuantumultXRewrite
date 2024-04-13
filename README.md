## 什么是Moodji？ / What's Moodji?
Moodji是一款弱化数据，强调情绪的健康管理软件。其中用户可以参与新年活动获取最新的皮肤，但是由于活动的限时性，用户只能获取一部分皮肤，或者干脆没有参与过。Moodji全皮肤脚本就是为了解决这个问题而生，它可以让你轻松无损地获取目前所有的皮肤。

Moodji is a health management software that weakens data and emphasizes emotions. Users can participate in the New Year's event to get the latest skin, but due to the limited time of the event, users can only get some skins, or they simply have not participated. This script is born to solve this problem, it can allow you to easily and losslessly obtain all the current skins.

## 预览
![image](https://github.com/qwe1187292926/MyQuantumultXRewrite/blob/feture-moodji-20240302/Moodji/readme/moodji_preview.png?raw=true)
![image](https://raw.githubusercontent.com/qwe1187292926/MyQuantumultXRewrite/feture-moodji-20240302/Moodji/readme/moodji_skin.png)

## 如何使用 Moodji 全皮肤 / How to use Moodji skin patch
首先你需要有 QuantumultX /Surge 其中之一，确定后跟随下面指引进行配置。

First, you need to have QuantumultX / Surge, and then follow the instructions below to configure.

QX:
```properties
^https?:\/\/moodji.api.flowzland.com\/[\/]?moodjiallinone\/v1\/getownproductlist url script-response-body https://raw.githubusercontent.com/qwe1187292926/MyQuantumultXRewrite/main/Moodji/skin.min.js
```

Surge4 (我没有Surge4，所以不确定下面是否能正常使用) (I'm not sure if it doesn't work, I don't have a Surge4 account):
```properties
http-response ^https?:\/\/moodji.api.flowzland.com\/[\/]?moodjiallinone\/v1\/getownproductlist requires-body=1,script-path=https://raw.githubusercontent.com/qwe1187292926/MyQuantumultXRewrite/main/Moodji/skin.min.js
```

Surge & QX 
```properties
MITM = moodji.api.flowzland.com
```

最后，清除缓存，重启软件，然后打开 Moodji，你会发现皮肤列表会自动更新。

Finally, clear the cache, restart the software, and then open Moodji, you will find that the skin list has updated.

