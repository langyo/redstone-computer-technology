# 红石计算机资料库索引

大家好，我是 langyo。

相信大家看见国内外讨论区不断有新的计算机存档发布，都亦希望能够掌握这种黑科技。但没有能力建造，网上五花八门的教程又过于零散，不系统，也不详细，尽是模仿，没有多少原理讲解。所以发布此贴，希望能帮到大家。

才疏学浅，还望技术大牛们指正！

> 此索引原本位于 [MCBBS](http://www.mcbbs.net/thread-492527-1-1.html)，为方便跳转而创建。一般情况下，此索引与位于 MCBBS 的索引同步更新，但大部分内容将只放在 Github。


***


## [“0”与“1”](https://langyo.github.io/redstone-computer-techiology/%E2%80%9C0%E2%80%9D%E4%B8%8E%E2%80%9C1%E2%80%9D)
“0”与“1”，两个平凡的数字，因为计算机的出现而熠熠生辉，支持着信息时代的发展。“0”与“1”属于二进制，而计算机内部的奥秘便与二进制息息相关。

学习有关进制的知识，对进一步学习计算机的内部结构会起到很大的作用。

此章节的目录：
* [什么是进制](https://langyo.github.io/redstone-computer-techiology/%E2%80%9C0%E2%80%9D%E4%B8%8E%E2%80%9C1%E2%80%9D#%E4%BB%80%E4%B9%88%E6%98%AF%E8%BF%9B%E5%88%B6)
* [二进制的计数原理与基本运算](https://langyo.github.io/redstone-computer-techiology/%E2%80%9C0%E2%80%9D%E4%B8%8E%E2%80%9C1%E2%80%9D#%E4%BA%8C%E8%BF%9B%E5%88%B6%E7%9A%84%E8%AE%A1%E6%95%B0%E5%8E%9F%E7%90%86%E4%B8%8E%E5%9F%BA%E6%9C%AC%E8%BF%90%E7%AE%97)
* [二进制与十进制间的转换方法](https://langyo.github.io/redstone-computer-techiology/%E2%80%9C0%E2%80%9D%E4%B8%8E%E2%80%9C1%E2%80%9D#%E4%BA%8C%E8%BF%9B%E5%88%B6%E4%B8%8E%E5%8D%81%E8%BF%9B%E5%88%B6%E9%97%B4%E7%9A%84%E8%BD%AC%E6%8D%A2%E6%96%B9%E6%B3%95)
* [十六进制的计数原理与基本运算](https://langyo.github.io/redstone-computer-techiology/%E2%80%9C0%E2%80%9D%E4%B8%8E%E2%80%9C1%E2%80%9D#%E5%8D%81%E5%85%AD%E8%BF%9B%E5%88%B6%E7%9A%84%E8%AE%A1%E6%95%B0%E5%8E%9F%E7%90%86%E4%B8%8E%E5%9F%BA%E6%9C%AC%E8%BF%90%E7%AE%97)
* [十六进制与十进制、二进制间的转换方法](https://langyo.github.io/redstone-computer-techiology/%E2%80%9C0%E2%80%9D%E4%B8%8E%E2%80%9C1%E2%80%9D#%E5%8D%81%E5%85%AD%E8%BF%9B%E5%88%B6%E4%B8%8E%E5%8D%81%E8%BF%9B%E5%88%B6%E5%8F%8A%E4%BA%8C%E8%BF%9B%E5%88%B6%E9%97%B4%E7%9A%84%E8%BD%AC%E6%8D%A2%E6%96%B9%E6%B3%95)
* [任意进制的计数原理、表达方法与基本运算](https://langyo.github.io/redstone-computer-techiology/%E2%80%9C0%E2%80%9D%E4%B8%8E%E2%80%9C1%E2%80%9D#%E4%BB%BB%E6%84%8F%E8%BF%9B%E5%88%B6%E7%9A%84%E8%AE%A1%E6%95%B0%E5%8E%9F%E7%90%86%E5%8F%8A%E8%A1%A8%E8%BE%BE%E6%96%B9%E6%B3%95%E4%B8%8E%E5%9F%BA%E6%9C%AC%E8%BF%90%E7%AE%97)
* [任意进制间的转换方法](https://langyo.github.io/redstone-computer-techiology/%E2%80%9C0%E2%80%9D%E4%B8%8E%E2%80%9C1%E2%80%9D#%E4%BB%BB%E6%84%8F%E8%BF%9B%E5%88%B6%E9%97%B4%E7%9A%84%E8%BD%AC%E6%8D%A2%E6%96%B9%E6%B3%95)

## [表达信息](https://langyo.github.io/redstone-computer-techiology/%E8%A1%A8%E8%BE%BE%E4%BF%A1%E6%81%AF)
计算机有着自己的语言。无论是不断变化着电压高低的电信号，还是经过一定转换得到的一串又一串的二进制数字，都需要为其定制一些编码方法。能够正确地表达信息，是计算机能够处理信息的必备条件之一。接下来，我们便开始了解一些最基础的有关信息本身的奥秘。

此章节的目录：
* [什么是信息](https://langyo.github.io/redstone-computer-techiology/%E8%A1%A8%E8%BE%BE%E4%BF%A1%E6%81%AF#%E4%BB%80%E4%B9%88%E6%98%AF%E4%BF%A1%E6%81%AF)
* [字长与大端序、小端序](https://langyo.github.io/redstone-computer-techiology/%E8%A1%A8%E8%BE%BE%E4%BF%A1%E6%81%AF#%E5%AD%97%E9%95%BF%E4%B8%8E%E5%A4%A7%E7%AB%AF%E5%BA%8F%E5%8F%8A%E5%B0%8F%E7%AB%AF%E5%BA%8F)
* [字符编码与 BCD 码](https://langyo.github.io/redstone-computer-techiology/%E8%A1%A8%E8%BE%BE%E4%BF%A1%E6%81%AF#%E5%AD%97%E7%AC%A6%E7%BC%96%E7%A0%81%E4%B8%8EBCD%E7%A0%81)
* [原码、反码与补码](https://langyo.github.io/redstone-computer-techiology/%E8%A1%A8%E8%BE%BE%E4%BF%A1%E6%81%AF#%E5%8E%9F%E7%A0%81%E5%8F%8A%E5%8F%8D%E7%A0%81%E4%B8%8E%E8%A1%A5%E7%A0%81)
* [定点数与浮点数](https://langyo.github.io/redstone-computer-techiology/%E8%A1%A8%E8%BE%BE%E4%BF%A1%E6%81%AF#%E5%AE%9A%E7%82%B9%E6%95%B0%E4%B8%8E%E6%B5%AE%E7%82%B9%E6%95%B0)

## 你好，红石！
> 正在编辑

红石电路是 Minecraft 的一大游戏特色。它模拟了现实中的一些电气元件，使得我们可以在游戏中建造各种各样的“电路”。依据应用方向与方式的不同，可以将具体的红石电路分为机械电路、模拟电路与数字电路三大类。

学会如何设计与建造红石电路，你可以做到在生存模式中解放你的双手、实现资源生产自动化，也可以在创造模式中放开手脚去模仿现实中的机械、集成电路。这是片任凭创造力与想象力自由飞翔的世界！

先对红石打个招呼吧！它与它们的搭档们是我们完成这样的伟作所需的必备工具。

> 此章节将同时在 Github 与 MCBBS 发布。

此章节的目录：
* 红石的本质
* 红石的搭档们
* 机械电路：用活塞推动世界
* 模拟电路：用一根线演绎千姿百态
* 数字电路：用“0”与“1”描述万物
* 红石电路的特性：时序与信号锁定
* 红石电路的特性：BUD 与 CUD
* 红石电路的特性：微延迟与无延迟
