# N-DecodeAllUnicode
Burpsuite插件：自动解码Burpsuite中被Unicode编码的内容（unicode -> utf8）

插件原作者：https://github.com/KagamigawaMeguri/burp-UnicodeAutoDecode
> 感谢插件原作者的插件分享！

## 修改如下
1、原插件只解码了 Intruder 模块和 Repeater 模块，修改后连同 HTTP history 内的 Response 数据也解码；

2、原插件解码存在失败的可能（这个应该是bug），修改后暂未发现解码失败的案例；

3、原解码成功的内容前后会自动加上【--u--】，个人感觉看起来不太习惯，修改后插件只做解码操作，不留下任何标记。

## 文档
[Burpsuite Unicode解码插件修改](https://www.yuque.com/no001ce/blog/hl02qk)
