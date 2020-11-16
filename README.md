# jisuye-ext
极速页-助手 谷歌浏览器插件配置
## 配置说明
```json
{
  "g": { // google.com
    "jpi": "input[name=q]", // 输入框定位
    "list": ".g", // 搜索结果列表
    "tip": "a>h3" // 快捷键显示位置
  },
  "d": ...,// baidu.com
  "b": ...,// bing.com
  "e": ..., // dogedoge.com
  "so": ..., // so.com
  "s": ..., //  sogou.com.cn
  "y": ...// yohoo.com.cn
}
```

# 插件安装方法
## 在线安装
谷歌应用商店： https://chrome.google.com/webstore/detail/%E6%9E%81%E9%80%9F%E9%A1%B5-%E5%8A%A9%E6%89%8B/knglannafmmagfbkoobfcpnapjbhmpgd?hl=zh-CN
## 离线安装
地址： https://jisuye.com/chrome/jisuye.crx

# 使用&功能
> 安装后默认可用如果出现各别搜索不显示快键键的情况，请在插件配置中联网更新（仍然无效可自己尝试修改配置，或在该项目下提交issue）

插件功能类似 vimium,  比之精简且默认开启快捷方式，减少一次按键，使用中会有冲突如果安装了vimium建议在搜索网站上禁用  

支持搜索网站：
1. google.com
2. bing.com
3. so.com
4. sogou.com
5. baidu.com
6. dogedoge.com
7. yohoo.com.cn

## 快捷访问
访问常用搜索引擎会自动对搜索结果添加快捷键，在搜索结果页面按对应按键打开对应链接

## 快速输入
在搜索结果页面按`i` 光标定位到搜索输入框

## 快速翻页
在搜索结果页面按 `p` 上翻一页查询结果，`n`下翻一页查询结果

## 结合极速页功能
插件中有一部分结合极速页(https://jisuye.com)  的功能  
如果登录了极速页，可以在浏览网页的过程中，一键收藏当前网址或者添加到极速页首页显示   
还可以发布到极速页的分享里
