# ChineseMongirlPedia
用于中文萌娘百科的拓展
# Using
```php
//该函数用于清空中文萌娘百科沙盒
//目前只支持大小为16字节的沙箱
ext_zhmg_clean_sandbox($sandboxname="Help:沙盒")

//该函数用于当{{急需改进}}{{不完整}}同时出现在一个条目内时去掉{{不完整}}
//https://zh.moegirl.org/index.php?title=%E7%A8%8B%E5%BA%8F%E5%91%98%E6%8B%9B%E5%8B%9F%E4%B8%AD&oldid=135505
ext_zhmg_clean_a()

//该函数用于将用户页中的{{人物信息}}替换为{{用户信息}}
//https://zh.moegirl.org/index.php?title=User_talk:Baskice&oldid=106897
ext_zhmg_clean_b()

//该函数用于将条目中的{{用户信息}}替换为{{人物信息}}
//https://zh.moegirl.org/index.php?title=User_talk:Baskice&oldid=106897
ext_zhmg_clean_c()

//该函数用于将条目名包含一个中文冒号：时自动将其换为英文冒号:并且不保留重定向
//https://zh.moegirl.org/index.php?title=User_talk:Baskice&oldid=106897
ext_zhmg_clean_d()

//该函数用于条目名包含中文括号（）时,自动将其换为英文括号().如果有人保持维基习惯,写_(的,去掉_
//https://zh.moegirl.org/index.php?title=User_talk:Baskice&oldid=106897
ext_zhmg_clean_e()

```
