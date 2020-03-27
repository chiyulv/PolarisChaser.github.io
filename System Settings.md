


# System Settings



---

## Install Driver

1.[Nvidia Driver](https://www.geforce.cn/drivers "Nvidia Driver")

2.[Logitech Drive](https://support.logi.com/hc/zh-cn/articles/360024361233 "Logitech Drive")

3.[God of War Driver[^1]](http://www.hasee.com/Chinese/drivers/drivers/index.php/Download/Index/model.html?id=311 "God of War Driver")

- My APP

- Synaptic

  
---
## Library

1.Move all library to:  <font color=MediumPurple>**D:\Library**</font>

2.<font color=IndianRed>**Unlink this PC**</font> in OneDrive

3.<font color=IndianRed>**Reset**</font> OneDrive Files



---

## Optimize Drives

1.Right click <font color=IndianRed>**operating system**</font> & click <font color=IndianRed>**properties**</font>

2.Click <font color=IndianRed>**tools**</font> & click <font color=IndianRed>**optimize**</font>

3.Turn <font color=IndianRed>**off**</font> <font color=Khaki>**optimize drives**</font> 



---

## Virtual Memory

1.Right click <font color=IndianRed>**this PC**</font> & click <font color=IndianRed>**properties**</font>

2.Click <font color=IndianRed>**remote settings**</font> & click <font color=IndianRed>**advanced/performance/settings**</font>

3.Click <font color=IndianRed>**advanced/virtual memory/change**</font>



|      Drive       | Paging File Size |
| :--------------: | :--------------: |
| operating system |       None       |
|     Library      |  System managed  |



---

## Power Options

1.Run <font color=IndianRed>**Windows PowerShell as administrator**</font>

2.Input 



```powershell
powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61
```



3.Plans shown on the battery meter: <font color=IndianRed>**Ultimate Performance**</font>

4.Change<font color=IndianRed> **plan settings**</font>



|       plan settings       | On battery | Plugged in |
| :-----------------------: | :--------: | :--------: |
|   Turn off the display    |   Never    |   Never    |
| Put the computer to sleep |   Never    |   Never    |



5.Change <font color=IndianRed>**choose what closing the lid does**</font>



| choose what closing the lid does | On battery | Plugged in |
| :------------------------------: | :--------: | :--------: |
|  When I press the power button   | Shut down  | Shut down  |
|  When I press the sleep button   |   Sleep    |   Sleep    |
|       When I close the lid       | Do nothing | Do nothing |



---

## Clipboard

1.Click <font color=IndianRed>**settings**</font> & click <font color=IndianRed>**system**</font>

2.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**clipboard history**</font>

3.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**Sync across devices**</font>



---

## Sticky Keys

1.Click <font color=IndianRed>**settings**</font> & click <font color=IndianRed>**system**</font>

2.Turn <font color=IndianRed>**off**</font> <font color=Khaki>**allow the shortcut key to start sticky keys**</font>



---

## Mouse

1.Click <font color=IndianRed>**settings**</font> & click <font color=IndianRed>**devices**</font>

2.Click <font color=IndianRed>**Mouse**</font>

3.Click <font color=IndianRed>**additional mouse options**</font>

4.Click <font color=IndianRed>**pointer options**</font>

5.Turn <font color=IndianRed>**off**</font> <font color=Khaki>**enhance pointer precision**</font>



---

## Sync My Phone

1.Click <font color=IndianRed>**settings**</font> & click <font color=IndianRed>**phone**</font>

2.Click <font color=IndianRed>**add a phone**</font>



---

## About App

1.Click <font color=IndianRed>**settings**</font> & click <font color=IndianRed>**apps**</font>

2.Uninstall

3.Updates

4.Download <font color=IndianRed>**Dolby Access**</font>,<font color=IndianRed>**Office**</font>,<font color=IndianRed>**tile Genie**</font>,<font color=IndianRed>**Quicklook**</font>,<font color=IndianRed>**Microsoft to do**</font>

+ Download plugins for [quicklook](https://github.com/QL-Win/QuickLook/wiki/Available-Plugins "quicklook"):
  + Office Viewer-Native,
  + Helix Viewer,
  + Font Viewer

5.Office Plugin

+ [iSlide](https://www.islide.cc/download "iSlide")

  1.Destination folder:  <font color=MediumPurple>**D:\iSlide**</font>  **(Install)**

+ [PocketAnimation](http://www.papocket.com/ "PocketAnimation")

  1.Destination folder:  <font color=MediumPurple>**D:\Pocket Animation**</font>  **(Install)**

+  [MyScript Math Sample](https://store.office.com/addinsinstallpage.aspx?rs=en-001&assetid=WA104380646 "MyScript Math Sample")

+ [Grammarly](https://www.grammarly.com/office-addin/windows "Grammarly")

+ [OneNote Gem](http://cn.onenotegem.com/a/addins/gem-menu-for-onenote-uwp.html "OneNote Gem")[^2]

  1.Destination folder:  <font color=MediumPurple>**D:\OneAppGemMenu**</font>  **(Install)**

  2.<font color=IndianRed>**Login in**</font> OneNote  **(Online)**

6.Outlook

1.Restart <font color=IndianRed>**POP3/SMTP Service**</font>

2.Open <font color=IndianRed>**Outlook**</font> & turn <font color=Khaki>**on manual setting**</font>

3.Click <font color=IndianRed>**POP**</font>

4.server1:  <font color=MediumPurple>**pop.qq.com**</font>

5:port:  <font color=MediumPurple>**995**</font>

6.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**SSL/TLS**</font>

7.server2:  <font color=MediumPurple>**smtp.qq.com**</font>

8:port2:  <font color=MediumPurple>**465**</font>

9.Encryption:  <font color=MediumPurple>**SSL/TLS**</font>

10.Input <font color=IndianRed>**password**</font>

7.Set the default startup app

---

## Startup

1.<font color=IndianRed>**Ctrl**</font>  +  <font color=IndianRed>**Shift**</font>   +    <font color=IndianRed>**Esc**</font>

2.Click <font color=IndianRed>**startup**</font>

3.<font color=IndianRed>**Disable**</font> Unnecessary app



---

## [Edge](https://www.microsoft.com/en-us/edge "Edge")

1.Theme:  <font color=MediumPurple>**Dark**</font>  **(Appearance)**

2.Show favorites bar:  <font color=MediumPurple>**Never**</font>  **(Appearance)**

3.Turn <font color=IndianRed>**off**</font> <font color=Khaki>**show favorites button**</font>  **(Appearance)**

4.On startup:  <font color=MediumPurple>**Continue where you left off**</font>  **(On startup)**

5.Turn <font color=IndianRed>**off**</font> <font color=Khaki>**continue running background apps when Microsoft Edge is closed**</font>  **(System)**

6.Plugin

+ [Tampermonkey](https://microsoftedge.microsoft.com/addons/detail/iikmkjmpaadaobahmlepeloendndfphd?hl=zh-CN "Tampermonkey")  <font color=YellowGreen>**(Move to the menu)**</font>

  [Gouwudang](https://greasyfork.org/zh-CN/scripts/14466-%E8%B4%AD%E7%89%A9%E5%85%9A%E8%87%AA%E5%8A%A8%E6%AF%94%E4%BB%B7%E5%B7%A5%E5%85%B7-%E9%A2%86%E5%8F%96%E6%B7%98%E5%AE%9D%E5%86%85%E9%83%A8%E5%88%B8 "Gouwudang")

  [Bilibili Evolved](https://greasyfork.org/zh-CN/scripts/373563-bilibili-evolved "Bilibili Evolved")

  1.Default player mode:  <font color=MediumPurple>**widescreen**</font>  **(Video)**

  2.Default player quality:  <font color=MediumPurple>**1080P60**</font>  **(Video)**

  3.Turn <font color=IndianRed>**off**</font> <font color=Khaki>**automatically expand the barrage list**</font>  **(Video)**

  4.Turn <font color=IndianRed>**off**</font> <font color=Khaki>**automatically expand the video profile**</font>  **(Video)**

  5.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**autoplay video**</font>  **(Video)**

  6.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**ignore acknowledgments**</font>  **(Video)**

  7.automatically locate to player:  <font color=MediumPurple>**50**</font>  **(Video)**

  8.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**double click for full screen**</font>  **(Video)**

  9.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**use season logo**</font>  **(Style)**

  10.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**compact layout**</font>  **(Style)**

  11.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**background blur**</font>  **(Style)**

  12.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**compact layout in home page**</font>  **(Style)**

  13.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**simplify the comments**</font>  **(Style)**

  14.Simplify the home page:  <font color=MediumPurple>**Clean**</font>  **(Style)**

  15.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**hide the top banner**</font>  **(Style)**

  16.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**player projection**</font>  **(Style)**

  17.Turn <font color=IndianRed>**off**</font> <font color=Khaki>**forced retention of barrage**</font>  **(Style)**

  18.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**delete video title**</font>  **(Style)**

  19.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**hide the reviews**</font>  **(Style)**

  20.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**hide the contract**</font>  **(Style)**

  21.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**hide the live**</font>  **(Style)**

  22.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**hide the other recommended**</font>  **(Style)**

  23.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**hide the partition**</font>  **(Style)**

  24.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**trend filter**</font>  **(trend)**

  25.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**simplify live**</font>  **(Live)**

  26.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**disable autoplay in home page**</font>  **(Live)**

  27.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**hide the live recommended**</font>  **(Live)**

  28.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**automatically receive**</font>  **(Live)**

  29.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**delete the e-sports**</font>  **(Tool)**

  30.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**hide the search referral**</font>  **(Tool)**

  31.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**bilibili plus**</font>  **(Tool)**

  32.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**automatically receive**</font>  **(Tool)**

  33.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**ajax hook API**</font>  **(Other)**

  34.Loading mode:  <font color=MediumPurple>**Simultaneously**</font>  **(Other)**

  [AC-baidu](https://greasyfork.org/zh-CN/scripts/14178-ac-baidu-%E9%87%8D%E5%AE%9A%E5%90%91%E4%BC%98%E5%8C%96%E7%99%BE%E5%BA%A6%E6%90%9C%E7%8B%97%E8%B0%B7%E6%AD%8C%E6%90%9C%E7%B4%A2-%E5%8E%BB%E5%B9%BF%E5%91%8A-favicon-%E5%8F%8C%E5%88%97 "AC-baidu")

  1.Baidu mode:  <font color=MediumPurple>**Default mode**</font>  **(Settings)**

  [Baidu's encyclopedia](https://greasyfork.org/zh-CN/scripts/16607-%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91-%E6%97%A0%E6%B0%B4%E5%8D%B0%E5%9B%BE%E7%89%87%E6%9F%A5%E7%9C%8B "Baidu's encyclopedia"),[Youtube](https://greasyfork.org/zh-CN/scripts/382426-youtube%E8%87%AA%E5%8A%A8%E5%88%87%E6%8D%A2%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95 "Youtube")

  [MoreMovieRatings](https://greasyfork.org/zh-CN/scripts/7687-moremovieratings "MoreMovieRatings"),[Enable right click](https://greasyfork.org/zh-CN/scripts/28497-remove-web-limits-modified "Enable right click")

  [Sleazyfork](https://greasyfork.org/zh-CN/scripts/23840-greasyfork-search-with-sleazyfork-results-include "Sleazyfork"),[Porn Video](https://sleazyfork.org/zh-CN/scripts/375267-porn-video%E4%B8%8B%E8%BD%BD-thisav-%E7%95%AA%E5%8F%B7-tag%E7%BF%BB%E8%AF%91-potplayer-%E6%92%AD%E6%94%BE "Porn Video")

  [MyDoubanMovieHelper](https://greasyfork.org/zh-CN/scripts/14636-mydoubanmoviehelper-%E8%B1%86%E7%93%A3%E7%94%B5%E5%BD%B1c-%E8%B1%86%E7%93%A3-%E8%B1%86%E7%93%A3%E7%94%B5%E5%BD%B1-movie-douban-com "MyDoubanMovieHelper"),[Clipboard clean](https://greasyfork.org/zh-CN/scripts/367724-%E7%9F%A5%E4%B9%8E-%E7%AE%80%E4%B9%A6-csdn-%E5%AE%9E%E9%AA%8C%E6%A5%BC%E5%89%AA%E5%88%87%E6%9D%BF%E6%B6%88%E6%AF%92 "Clipboard clean")

  [CSDN](https://greasyfork.org/zh-CN/scripts/378351-%E6%8C%81%E7%BB%AD%E6%9B%B4%E6%96%B0-csdn%E9%A1%B5%E9%9D%A2%E6%B5%AE%E7%AA%97%E5%B9%BF%E5%91%8A%E5%AE%8C%E5%85%A8%E8%BF%87%E6%BB%A4%E5%87%80%E5%8C%96-%E5%87%80%E5%8C%96%E5%A4%8D%E5%88%B6%E5%86%85%E5%AE%B9-%E8%87%AA%E5%8A%A8%E5%B1%95%E5%BC%80-%E8%AE%A9%E4%BD%A0%E4%B8%93%E6%B3%A8%E4%BA%8E%E6%96%87%E7%AB%A0-%E4%B8%8D%E5%BD%B1%E5%93%8D%E5%8A%9F%E8%83%BD%E4%BD%BF%E7%94%A8 "CSDN"),[Zhihu](https://greasyfork.org/zh-CN/scripts/384172-%E7%9F%A5%E4%B9%8E%E7%BD%91%E9%A1%B5%E5%8A%A9%E6%89%8B-5%E5%A4%A7%E5%8A%9F%E8%83%BD%E9%9B%86%E4%BA%8E%E4%B8%80%E8%BA%AB "Zhihu")

  [Baidu Netdisk](https://greasyfork.org/zh-CN/scripts/397390-%E7%99%BE%E5%BA%A6%E7%BD%91%E7%9B%98%E7%9B%B4%E9%93%BE%E4%B8%8B%E8%BD%BD%E5%8A%A9%E6%89%8B "Baidu Netdisk"),[Tieba](https://greasyfork.org/zh-CN/scripts/26992-%E8%B4%B4%E5%90%A7%E5%85%A8%E8%83%BD%E5%8A%A9%E6%89%8B "Tieba")

  [Baidu Netdisk Pro](https://greasyfork.org/zh-CN/scripts/29762-%E7%BD%91%E7%9B%98%E8%87%AA%E5%8A%A8%E5%A1%AB%E5%86%99%E5%AF%86%E7%A0%81-%E5%A8%81%E5%8A%9B%E5%8A%A0%E5%BC%BA%E7%89%88 "Baidu Netdisk Pro"),[ACG](https://sleazyfork.org/zh-CN/scripts/23316-%E7%90%89%E7%A5%9E%E8%BD%89 "ACG")

  [LimitBilibili](https://greasyfork.org/zh-CN/scripts/25718-%E8%A7%A3%E9%99%A4b%E7%AB%99%E5%8C%BA%E5%9F%9F%E9%99%90%E5%88%B6 "LimitBilibili"),[douban](https://greasyfork.org/zh-CN/scripts/329484-%E8%B1%86%E7%93%A3%E8%B5%84%E6%BA%90%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%B8%88-1%E7%A7%92%E6%90%9E%E5%AE%9A%E8%B1%86%E7%93%A3%E7%94%B5%E5%BD%B1-%E9%9F%B3%E4%B9%90-%E5%9B%BE%E4%B9%A6%E4%B8%8B%E8%BD%BD "douban")

  [Douyu](https://greasyfork.org/zh-CN/scripts/394497-douyuex-%E6%96%97%E9%B1%BC%E7%9B%B4%E6%92%AD%E9%97%B4%E5%A2%9E%E5%BC%BA%E6%8F%92%E4%BB%B6 "Douyu"),[Baidu](https://greasyfork.org/zh-CN/scripts/390817-%E7%99%BE%E5%BA%A6%E6%96%87%E5%BA%93%E8%B5%84%E6%96%99%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8A%A9%E6%89%8B "Baidu")

  [Picture](https://greasyfork.org/zh-CN/scripts/2312-resize-image-on-open-image-in-new-tab "Picture")

+ [Grammarly](https://microsoftedge.microsoft.com/addons/detail/cnlefmmeadmemmdciolhbnfeacpdfbkd?hl=zh-CN "Grammarly")  <font color=YellowGreen>**(Move to the menu)**</font>

+ [AdBlock — best ad blocker](https://microsoftedge.microsoft.com/addons/detail/ndcileolkflehcjpmjnfbnaibdcgglog?hl=zh-CN "AdBlock — best ad blocker")  <font color=YellowGreen>**(Move to the menu)**</font>

+ [Monknow new tab](https://microsoftedge.microsoft.com/addons/detail/ekpbeboofmnpohcmdnfkhjameokgffde?hl=zh-CN "Monknow new tab")  <font color=YellowGreen>**(Move to the menu)**</font>

+ [Vimium](https://microsoftedge.microsoft.com/addons/detail/aibcglbfblnogfjhbcmmpobjhnomhcdo?hl=zh-CN "Vimium")  <font color=YellowGreen>**(Move to the menu)**</font>

  1.Default search engine:

  ```http
  https://www.baidu.com/s?ie=utf-8&wd=%s 百度
  ```
2.Custom search engines:

  ```http
  g: https://www.google.com/search?q=%s Google
  G: https://www.google.com/search?q=%s Google
  zh: https://www.zhihu.com/search?type=content&q=%s 知乎
  ZH: https://www.zhihu.com/search?type=content&q=%s 知乎
  tb: https://s.taobao.com/search?q=%s 淘宝
  TB: https://s.taobao.com/search?q=%s 淘宝
  jd: https://search.jd.com/Search?keyword=%s 京东
  JD: https://search.jd.com/Search?keyword=%s 京东
  bd: https://www.baidu.com/s?wd=%s 百度
  BD: https://www.baidu.com/s?wd=%s 百度
  bz: https://search.bilibili.com/all?keyword=%s b站
  BZ: https://search.bilibili.com/all?keyword=%s b站
  az: https://www.amazon.com/s/?field-keywords=%s Amazon
  AZ: https://www.amazon.com/s/?field-keywords=%s Amazon
  aqy: https://so.iqiyi.com/so/q_%s 爱奇艺
  AQY: https://so.iqiyi.com/so/q_%s 爱奇艺
  tm: https://list.tmall.com/search_product.htm?q=%s 天猫
  TM: https://list.tmall.com/search_product.htm?q=%s 天猫
  yk: https://so.youku.com/search_video/q_%s 优酷
  YK: https://so.youku.com/search_video/q_%s 优酷
  db: https://www.douban.com/search?q=%s 豆瓣
  DB: https://www.douban.com/search?q=%s 豆瓣
  y: https://www.youtube.com/results?search_query=%s Youtube
  Y: https://www.youtube.com/results?search_query=%s Youtube
  ```

  3.Turn <font color=IndianRed>**off**</font> <font color=Khaki>**don't let pages steal the focus in loading**</font>  **(Miscellaneous options)**

+ [Saladict](https://microsoftedge.microsoft.com/addons/detail/idghocbbahafpfhjnfhpbfbmpegphmmp?hl=zh-CN "Saladict")

  1.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**dark mode**</font>  **(Dict panel)**

  2.panel max height ratio:  <font color=MediumPurple>**40%**</font>  **(Dict panel)**

  3.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**enalbe PDF sniffer**</font>  **(PDF)**

  4.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**auto search**</font>  **(Popup panel)**

  5.Set shortcut key:  <font color=MediumPurple>**Ctrl  +  E**</font>  **(Extensions)**

+ [PiP - Picture in Picture Plus](https://microsoftedge.microsoft.com/addons/detail/gokdpnhaggoioddclnnlpjfnkdinjjcc?hl=zh-CN "PiP - Picture in Picture Plus")  <font color=YellowGreen>**(Move to the menu)**</font>

+ [Nano Adblocker](https://microsoftedge.microsoft.com/addons/detail/epbkapkgcmdmfpogenoebpdeibmfinpf?hl=zh-CN "Nano Adblocker")  <font color=YellowGreen>**(Move to the menu)**</font>

+ [pakku](https://microsoftedge.microsoft.com/addons/detail/lnfcfeidnipnphibahlkdhalpkpmccoc?hl=zh-CN 
  "pakku")  <font color=YellowGreen>**(Move to the menu)**</font>

  1.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**reduces the font size when the barrage density is too high**</font>  **(Display settings)**
  
  2.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**Barrage density analysis diagram**</font>  **(Player enhancements)**
  
+ [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=zh-CN "Stylus")  <font color=YellowGreen>**(Move to the menu)**</font>

  [Bilibili1](https://userstyles.org/styles/171825/bilibili "Bilibili1"),[Bilibili2](https://userstyles.org/styles/170654/bilibili-2019 "Bilibili2")

  [Bilibili3](https://userstyles.org/styles/125049/bilibili "Bilibili3"),[Baidu1](https://userstyles.org/styles/173673/pure "Baidu1")

  [Baidu2](https://userstyles.org/styles/130739/theme "Baidu2"),[Baidu3](https://userstyles.org/styles/123597/theme "Baidu3")  <font color=YellowGreen>**(Download font)**</font>

  [Weibo1](https://userstyles.org/styles/158902/weibox "Weibo1"),[Weibo2](https://userstyles.org/styles/123737/weibo-v6-patch "Weibo2")

  [Taobao1](https://userstyles.org/styles/168403/theme "Taobao1"),[Youtube1](https://userstyles.org/styles/95033/youtube-nyan-cat-progress-bar-video-player-theme "Youtube1")

  [Youtube2](https://userstyles.org/styles/141088/fade-for-youtube "Youtube2"),[Youtube3](https://userstyles.org/styles/167450/colourful-youtube-ratings "Youtube3")

  [Youtube4](https://userstyles.org/styles/170083/you-youtube-logo-fixed "Youtube4"),[Tieba1](https://userstyles.org/styles/124770/tieba-maverick-2018 "Tieba1")

  [Zhihu1](https://userstyles.org/styles/159687/zhihux-v2 "Zhihu1"),[Huya1](https://userstyles.org/styles/170766/huya "Huya1")

  [CSDN1](https://userstyles.org/styles/172390/csdn "CSDN1"),[Google1](https://userstyles.org/styles/107767/google-2020-dark-custom-background-low-opacity "Google1")

  [Roblox1](https://userstyles.org/styles/179042/roblox-theme-doodled-clouds "Roblox1"),[Roblox2](https://userstyles.org/styles/177168/spinning-icon-for-roblox "Roblox2")

  [Roblox3](https://userstyles.org/styles/161197/roblox-cursor-complement-billyack "Roblox3")

+ [AHA Music](https://chrome.google.com/webstore/detail/aha-music-music-identifie/dpacanjfikmhoddligfbehkpomnbgblf?hl=zh-CN "AHA Music")

+ [Global Speed](https://microsoftedge.microsoft.com/addons/detail/mjhlabbcmjflkpjknnicihkfnmbdfced?hl=zh-CN "Global Speed")

  1.Set shortcut key subjust speed:  <font color=MediumPurple>**Ctrl  + Alt + 1**</font>  **(Shortcut Editor)**

  2.Set shortcut key set speed:  <font color=MediumPurple>**Ctrl  + Alt + 2**</font>  **(Shortcut Editor)**

  3.Set shortcut key adjust speed:  <font color=MediumPurple>**Ctrl  + Alt + 3**</font>  **(Shortcut Editor)**

  4.Set shortcut key seek -0.1:  <font color=MediumPurple>**Ctrl  + Alt + D**</font>  **(Shortcut Editor)**

  5.Set shortcut key seek 0.1 :  <font color=MediumPurple>**Ctrl  + Alt + F**</font>  **(Shortcut Editor)**

  6.Set shortcut key seek -5:  <font color=MediumPurple>**Ctrl  + Alt + E**</font>  **(Shortcut Editor)**

  7.Set shortcut key seek 5:  <font color=MediumPurple>**Ctrl  + Alt + R**</font>  **(Shortcut Editor)**

+ [Sourcegraph](https://chrome.google.com/webstore/detail/sourcegraph/dgjhfomjieaadpoljlnidmbgkdffpack?hl=zh-CN "Sourcegraph")  <font color=YellowGreen>**(Move to the menu)**</font>

+ [GitZip for github](https://chrome.google.com/webstore/detail/gitzip-for-github/ffabmkklhbepgcgfonabamgnfafbdlkn "GitZip for github")  <font color=YellowGreen>**(Move to the menu)**</font>

+ Internet download manager  <font color=YellowGreen>**(Move to the menu)**</font>

+ [Powerful Pixiv Downloader](https://chrome.google.com/webstore/detail/powerful-pixiv-downloader/dkndmhgdcmjdmkdonmbgjpijejdcilfh/related "Powerful Pixiv Downloader")  <font color=YellowGreen>**(Move to the menu)**</font>

+ [NooBoss](https://chrome.google.com/webstore/detail/nooboss/aajodjghehmlpahhboidcpfjcncmcklf "NooBoss")  <font color=YellowGreen>**(Move to the menu)**</font>

+ [Bookmarks sidebar](https://microsoftedge.microsoft.com/addons/detail/lmjefbghkfeppnpofmbfmhgodpclipbl?hl=zh-CN "Bookmarks sidebar")  <font color=YellowGreen>**(Move to the menu)**</font>

  1.Sidebar:  <font color=MediumPurple>**Right**</font>  **(Start)**

  2.Open sidebar:  <font color=MediumPurple>**Left Click**</font>  **(Start)**
  
  3.Typeface:  <font color=MediumPurple>**Microsoft YaHei UI**</font>  **(Appearance)**
  
  

---

## Personalize

1.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**show more tiles on start**</font>  **(Start)**

2.Turn <font color=IndianRed>**off**</font> <font color=Khaki>**show app list in start menu**</font>  **(Start)**

3.Turn <font color=IndianRed>**off**</font> <font color=Khaki>**show recently added apps**</font>  **(Start)**

4.Turn <font color=IndianRed>**on**</font> <font color=Khaki>**use start full screen**</font>  **(Start)**

5.Taskbar location on screen:  <font color=MediumPurple>**Top**</font>  **(Taskbar)**



---

## Startup

1.Create a txt

2.Input

```powershell
start "" "xx" & ping localhost -n x
```

xx[^3]

x[^4]

3.Renamed to <font color=MediumPurple>**"Startup.bat"**</font>

4.Move to:  <font color=MediumPurple>**C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp**</font>



[^1]: 1  Z7-KP7GT
[^2]: (1 PC,1 notebook,1 pad )
[^3]: program path
[^4]: Lag time