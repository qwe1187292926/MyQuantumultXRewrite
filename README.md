# MyQuantumultXRewrite
Obtain Moodji skin patch, it will add more in future.

## 如何使用 Moodji 全皮肤 / How to use Moodji skin patch
首先你需要有 QuantumultX /Surge 其中之一，确定后跟随下面指引进行配置。

First, you need to have QuantumultX / Surge, and then follow the instructions below to configure.

QX:
```properties
^https?:\/\/moodji.api.flowzland.com\/\/moodjiallinone\/v1\/getownproductlist url script-response-body https://raw.githubusercontent.com/qwe1187292926/MyQuantumultXRewrite/main/Moodji/skin.min.js
```

Surge4 (我没有Surge4，所以不确定下面是否能正常使用) (I'm not sure if it doesn't work, I don't have a Surge4 account):
```properties
http-response ^https?:\/\/moodji.api.flowzland.com\/\/moodjiallinone\/v1\/getownproductlist requires-body=1,script-path=https://raw.githubusercontent.com/qwe1187292926/MyQuantumultXRewrite/main/Moodji/skin.min.js
```

Surge & QX 
```properties
MITM = moodji.api.flowzland.com
```

最后，清除缓存，重启软件，然后打开 Moodji，你会发现皮肤列表会自动更新。

Finally, clear the cache, restart the software, and then open Moodji, you will find that the skin list has updated.

如果你喜欢我的工作，请给我Star呜呜呜。 If you like my work, I will be appreciated to have your star!

