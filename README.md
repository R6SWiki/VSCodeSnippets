# VSCodeSnippets
专用于VSCode编辑者可以使用的本站编辑工作的自定义代码片段补全方案文件。

不依赖其他插件。

## 使用方法

1. 在VSCode中按下`F1`
2. 搜索`Configure User Snippets`找到「首选项：配置用户代码片段」
3. 以Wikitext为例，在弹出的输入框中搜索并选择Wikitext
4. 之后会打开`Wikitext.json`文件，把本项目提供的Wikitext.json文件内容直接复制进去并保存即可使用。

### 语法提示


#### Wikitext


在行内使用的时候前面需要打一个`@`（位于esc键下方）；

前缀短语还没输入完的时候就会出现提示，根据需要使用方向键选择然后按Tab键即可。对于有多个参数的模板，在输入每一个参数后都按一下Tab即可切换到下一个参数；

可以根据自己的需求来定制修改语法提示文件。


- **skill**：技能名
- **mouse**：鼠标键
- **key**：键盘键
- **operatorCord**：干员名，只输入cord也可以触发
- **map**：地图名
- **mapid**：地图英文id
- **wi**：武器型号
- **quality**：涂装品质
- **color**：颜色
- **ref**：引用
- **正在施工**：{{正在施工}}
- **infoboxPatch**：补丁页面的infobox
- **operatorChangeItem**：干员改动模板
- **每周挑战**
	- **多人每周挑战**
	- **训练场每周挑战**
	- **大师每周挑战：**武器击杀任务
	- **进攻方每周挑战**
	- **防守方每周挑战**
	- **得分每周挑战**


#### html


html的部分主要就是替换了html5的语法，在里面补充了common.css的引用和默认的页面背景色。关于common.css的部分详见项目：R6SWiki/**[HTMLFront](https://github.com/R6SWiki/HTMLFront)**

####lua

准备中……

## 扩展


[了解Wikitext插件的使用方法](https://www.huijiwiki.com/p/21136) ｜ [Wikitext插件](https://marketplace.visualstudio.com/items?itemName=RoweWilsonFrederiskHolme.wikitext)