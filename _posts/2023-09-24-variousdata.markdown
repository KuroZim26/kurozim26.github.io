---
layout: post
title:  "其他杂项资料和娱乐文本"
date:	2023-09-24 00:00:00 +0800
---

本页面收录本人原存放在萌娘百科用户页面的杂项资料和娱乐性内容。

## 自留工具箱

### 通用的Bilibili封面提取手段

2020年3月23日，B站更改了视频番号系统，自该日起投稿的所有内容均只有BV号。对于该日前投稿的所有视频，其AV号仍然可用，但仅作为API中的标识而不再显示于网页前台。自该日起发布的，只有BV号作为番号的所有视频，实际上是仍然具有AV号的，且创作中心投稿时还会另外显示一个投稿序号。视频的AV号、BV号和投稿序号三者之间存在一一映射关系。

1. 封面直链调用站点：[galmoe](http://www.galmoe.com/)
* AV号和BV号均可用。

2. API调用
* API地址如下（问号处换成视频ID番号）：<br>
`https://api.bilibili.com/x/web-interface/view?bvid=bv??????????`<br>
`https://api.bilibili.com/x/web-interface/view?aid=av????????`
* 以[BV1UJ411F7Qy / av70396560](/2023/01/13/song03.html)为例，在支持json显示的浏览器（如本人目前使用的FireFox）中。应该是长这个样子的：
![这是图片](/assets/img/apiexample.png "Bilibili API调用示例 JSON格式")
图中pic行所指的链接就是封面链接。

### 一些自用的小工具

1. 外语在线输入法：[日语输入法](http://o-oo.net.cn/keyboard/) / [韩语输入法](http://www.ch2ko.com/ime.html)

2. 日期计算器：[bjtime](http://bjtime.cn/riqi/)

3. 颜色代码查询工具：[站长工具调色盘](http://tool.chinaz.com/Tools/onlinecolor.aspx) / [color-sample](https://www.color-sample.com/) / [sioe.cn工具](https://www.sioe.cn/yingyong/yanse-rgb-16/)

4. 微软开源工具PowerToys： [Github](https://github.com/microsoft/PowerToys/releases)
* 该工具内置取色器，在打开PowerToys的情况下按组合键（默认Win + Shift + C）可进入指针取色模式

5. PhotoShop的免费平替Photopea：[官方](https://www.photopea.com/) / [稿定设计](https://ps.gaoding.com/)
* 国内版访问更快，但需要账号才能正常使用。介意的话还是推荐官方版，其付费功能对实际使用完全无影响。

## 奇怪的游戏研究

### 明日方舟中的“百万队 / 765Production队”

“百万队”是一种以角色日语配音为基准的配队方式，属于娱乐性编队玩法。在2022年夏活前，该编队的整体强度一般，但鸿雪、百炼嘉维尔、缄默德克萨斯、纯烬艾雅法拉等强力干员的加入拉高了这种编队的整体强度。
* 本家队 / 狭义765队：队伍中仅包括日配演员参与<b>偶像大师本家系列（765PRO ALLSTARS）</b>的干员。
* 狭义百万队 / 广义765队：队伍中包括日配演员参与<b>偶像大师本家系列和百万现场系列（即765MILLION ALLSTARS）</b>的干员。
* 广义百万队 / 泛百万队 / MLTD队：队伍中包括日配演员参与<b>手游《偶像大师 百万现场 剧场时光》</b>的干员，除百万现场系列全角色外，还包括在MLTD中登场的其他子系列角色。

| 偶像角色 | 日语配音 | 所属 | 明日方舟中的同CV干员 | 备注 |
| :--: | :--: | :--: | :--: | :--: |
| 如月千早 | 今井麻美 | 765PRO ALLSTARS | ★★★★★：拉普兰德 | 百万队中的沉默担当，愚人号必备干员之一 |
| 萩原雪步 | 浅仓杏美 | 765PRO ALLSTARS | ★★★：卡缇<br>★★★★★：幽灵鲨<br>★★★★★★[限]：归溟幽灵鲨 | 配音的三名干员都有一定的站场能力<br>幽灵鲨更是因其一流的短期抗高压能力<br>拥有“危机合约指定重装”的爱称 |
| 菊地真 | 平田宏美 | 765PRO ALLSTARS | ★★★★★：铎铃 | 五星重剑手，石英上位 |
| 水濑伊织 | 钉宫理惠 | 765PRO ALLSTARS | ★★★★★★：艾丽妮 | 愚人号活动上岛，群控技能强力 |
| 双海亚美·真美 | 下田麻美 | 765PRO ALLSTARS | ★：Lancet-2<br>★★★★：红豆 | 医疗小车具有一定的战术应用潜力<br>红豆则以其身为四星的高输出被爱称为“常山豆子龙” |
| 春日未来 | 山崎遥 | 765MILLION ALLSTARS<br>PRINCESS STARS | ★★★★★[活]：格拉尼 | 骑猎活动奖励干员，防卫型冲锋手定位独特 |
| 田中琴叶 | 种田梨沙 | 765MILLION ALLSTARS<br>PRINCESS STARS | ★★★★★：陨星<br>★★★★★★：艾雅法拉<br>★★★★★★[限]：纯烬艾雅法拉 | 陨星，高输出爆破型群狙，特定场合战术价值高<br>艾雅法拉，毋庸置疑的开服最强单法<br>纯烬艾雅法拉，可日常单奶可对抗元素损伤<br>推出后被公认为目前医疗中的第一梯队<br>反正就还是种田比较适合老子（ |
| 德川茉莉 | 诹访彩花 | 765MILLION ALLSTARS<br>PRINCESS STARS | ★★★★：蛇屠箱<br>★★★★[兑]：嘉维尔<br>★★★★★：狮蝎<br>★★★★★★[限]：百炼嘉维尔 | 蛇屠箱物防能力优秀，二技能是独特的挡四流<br>嘉维尔可用作日常医疗使用<br>狮蝎地刺模板稳定群控<br>百嘉作为夏活限定也相当强势 |
| 松田亚利沙 | 村川梨衣 | 765MILLION ALLSTARS<br>PRINCESS STARS | ★★★★★[活]：苦艾 | 真·梨衣熊<br>一技能永续增强，二技能收残血 |
| 高坂海美 | 上田丽奈 | 765MILLION ALLSTARS<br>PRINCESS STARS | ★★★★★★：早露 | 六星重狙，束缚技能在特定环境下有奇效 |
| 最上静香 | 田所梓 | 765MILLION ALLSTARS<br>FAIRY STARS | ★★★：克洛丝<br>★★★★★：德克萨斯<br>★★★★★[活]：寒芒克洛丝<br>★★★★★★[限]：缄默德克萨斯 | 著名的kokodayo（略<br>克洛丝+德克萨斯由于容易获取从而在开局阶段比较常用<br>寒芒克洛丝增加了晕眩技能和攻速，战术价值提升<br>缄默德克萨斯作为限定特种，强度超高 |
| 永吉昴 | 齐藤佑圭 | 765MILLION ALLSTARS<br>FAIRY STARS | ★★★★★：晓歌 | 你们一定要练晓歌啊.jpg<br>晓歌打棒球激怒艾雅法拉.jpg |
| 马场木实 | 高桥未奈美 | 765MILLION ALLSTARS<br>ANGEL STARS | ★★★★★[活]：鞭刃 | 玛莉亚临光活动奖励干员，教官模板强度一般 |
| 青羽美咲 | 安济知佳 | 765 Production<br>剧场事务员 | ★★★★★★：鸿雪 | 著名的10万大c |
| 诗花 | 高桥李依 | 961 Production 所属<br>MLTD EX阵营 | ★★★★：调香师<br>★★★★★：夜魔 | |
| 一之濑志希 | 蓝原琴美 | 346 Production 所属<br>MLTD EX阵营 | ★★★★★[兑]：埃拉托 | |
| 宫本芙蕾德莉卡 | 高野麻美 | 346 Production 所属<br>MLTD EX阵营 | ★★★★★：夏栎 | |

## 梗 / meme / Neta

### 一个缩写的不同含义

#### LS

* 可以是《一花依世界》的作曲LS大大。
* 可以是韩国第一个BOF冠军团队Lunatic Sounds (现称Cosmograph)。
* 当然有一张东方同人专辑也叫LUNATIC SOUNDS，东方众们请不要搞混。
* 可以是温柔可爱的前辈Luna Safari。
* 也可以是雅马哈LS型号的吉他。
* 还可以是PVZ里面的小游戏Last Stand（谁笑到最后 / 坚不可摧）。
* 也可以是常用于论坛、评论区的用词「楼上」的音序（Lou Shang）。
* 也可以是Liberal studies（通识课），曾经是香港中学的一个必修课。

#### TP

* 在腾讯，TP是反外挂系统Tencent Protect。
* 在偶像大师灰姑娘女孩，TP是Cool系组合Triad Primus；当然还有这组合的标志性曲目Trancing Pulse。
* 在Minecraft，TP是传送指令。
* 在公主连结 Re:Dive，TP是技能值。
* 在Cytus系列，TP是Technical Points，准度的标志。
* 在同步音律喵赛克，TP是Terminated Protocol，9级最难之一。
* 在舰队Collection，TP是运输量。
* 在DotA2，TP是回城卷轴。
* 在地理意义上，TP也可以是台北（Taipei）的简写，比如AKB48 TEAM TP。
* 或者是TP （Tropical Premium），泰国水果品牌。
* TP-Link路由器，谁用谁SB。
* 当然如果非要说的话，音游曲师Technoplanet也可以简称TP。

### 小合集：我们一起学？？？叫

* [我们一起学脑力叫，一起O-oooooooooo AAAAE-A-A-I-A-U- JO-oooooooooooo AAE-O-A-A-U-U-A- E-eee-ee-eee AAAAE-A-E-I-E-A- JO-ooo-oo-oo-oo EEEEO-A-AAA-AAAA](https://www.bilibili.com/video/av30966284?p=1)
* [我们一起学Roselia叫，一起R R R R R，在你身边One's Intention，哎哟R R R R R](https://y.qq.com/n/ryqq/songDetail/001fiqOz0PXis3)
* [我们一起学星尘叫，一起啦啦啦啦啦啦啦啦啦啦啦啦啦啦啦……](https://www.bilibili.com/video/av3896979?p=1)

### 杂梗收录

1. [浴霸泽志保](https://www.acfun.cn/v/ac32614874_1)
* [谁会！在打Marionetteは眠らない的时候！直球玩浴霸梗啊！](https://www.bilibili.com/video/BV18W411K7oY)
2. （某大触发了一张Cytus 里FD TP99+的成绩图）<br>萌新：您这个里FD也太强了吧<br>大触：强个鬼，打得跟特么狼的大招似的<br>萌新：高输出还能破甲？！<br>大触：破你妈，一堆MISS！<br>PCR玩家：难道不是鸭梨瞎的大招？
3. 准度冠绝Cytus圈的Tento，在Cytus II，由于空间判定变窄的原因会出现大量MISS；UB快、伤害高的亚里莎，在Rank10之前经常因为不明原因出现大量MISS。这么一想，Tento和亚里莎贴贴？！
4. 在第529、530、531期周刊虚拟歌手中文曲排行榜中，普通Disco拿下了它生涯的第九次SUPER HIT。不过联想到近期的那款令人PTSD的游戏……只能说，谢谢你，羊了个羊。 