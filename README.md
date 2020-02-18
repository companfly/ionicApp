# ionicApp
test git and github

feature-A
- fix-B
- faeture-C
# 手机品牌检测
function Browser () {
          var ug = navigator.userAgent
          var device = navigator.userAgent.match(/\(.*AppleWebKit/)
          this.wechat = /micromessenger/i.test(ug)
          this.isBaidu = /baidu/i.test(ug)
          this.isHuaweibrowser = /HuaweiBrowser/.test(ug)
          this.vivo =  /V\d{4}[A-Z]/.test(device)
          this.huawei = /(AL00|AL10|AL20|UL10|TL00|UL00|CL20|TL00H|CL00|AL40|DL00|W09|TL10|AN00|AN00P|QL10|AL0|Al10|T00|L03|TL00M|TL20|AL00X|AN10)/.test(device)
          this.oppo = /P[A_Z]{3}\d{2}/.test(device)
          this.ios = /(iPhone|iPad|iPod|iOS)/i.test(ug)
          this.android = /android/i.test(ug)
        }
