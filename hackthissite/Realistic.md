### Uncle Arnold's Local Band Review

**问题描述：**

一个傻叉乐队的头头：hi，哥们，我需要你的帮忙。是这样的，我以前和别人打了一个500刀的赌，如果我的乐队能在年终排到[这个网站](https://www.hackthissite.org/missions/realistic/1/)的第一位我就赢了。问题是我有两个乐队成员出了车祸挂掉了，并且那个混蛋还坚持要赌，What an asshole。

我知道你精通计算机，你看你能不能帮我赢这个赌，让我乐队的名字排到第1，乐队名字是Raging Inferno。

**解答：**

查看网页源代码，你可以看到vote表单使用v.php。这意味这你可以直接更改rating。

![band](https://github.com/tiancode/start-learn-kali-linux/blob/master/hackthissite/image/Screen%20Shot%202016-05-10%20at%2019.49.18.png)

直接访问下面网址更改投票数：

```
https://www.hackthissite.org/missions/realistic/1/v.php?PHPSESSID=abcaeadfc31a5c43b2534bf995c0553f&id=3&vote=777
```

### Chicago American Nazi Party
