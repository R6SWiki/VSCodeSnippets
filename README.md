专用于VSCode编辑者可以使用的本站编辑工作的自定义代码片段补全方案文件。

不依赖其他插件。

## 使用方法


这里提供两个方案：


- 直接[下载](https://github.com/R6SWiki/VSCodeSnippets/releases)文件拷贝到你的工作区中的`.vscode`目录下，搞定，这是最简单的方式！
- 如果你的需求比较复杂，则可以这样：
	1. 在VSCode中按下`F1`
	2. 搜索`Configure User Snippets`找到「首选项：配置用户代码片段」
	3. 在弹出的框中选择「新建“XXXX”文件夹的代码片段文件。」，所谓的XXXX就是你的工作区。
	4. 在弹出的框中输入你要的名字，比如`R6swiki`，完成后会新建一个`R6swiki.code-snippet`文件。
	5. 根据需要把本项目提供的`wikitext.json`或者`lua.json`文件内容直接复制进去并保存即可使用。

### 语法提示


#### Wikitext


在行内使用的时候前面需要在前面打一个空格可以确保稳定触发；

前缀短语还没输入完的时候就会出现提示，根据需要使用方向键选择然后按Tab键即可。对于有多个参数的模板，在输入每一个参数后都按一下Tab即可切换到下一个参数；

可以根据自己的需求来定制修改语法提示文件。


- **skill**：技能名
- **mouse**：鼠标键
- **key**：键盘键
- **operatorCode**：干员名，只输入cord也可以触发
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
	- **大师每周挑战**：武器击杀任务
	- **进攻方每周挑战**
	- **防守方每周挑战**
	- **得分每周挑战**

#### lua


mediawiki函数库的语法提示支持请使用：[Lua snippets for Wikimedia插件](https://marketplace.visualstudio.com/items?itemName=jeblad-3.WMFsnippets)


- **lua**：快速开始一个模块
- **find**：数据查询
- **findOne**：查询1行数据

#### html


html的部分主要就是替换了html5的语法，在里面补充了common.css的引用和默认的页面背景色。这一部分主要考虑到网页开发的部分工作，因此并没有放在本项目中，如果需要请前往：R6SWiki/**[HTMLFront](https://github.com/R6SWiki/HTMLFront)**

## 扩展


[了解如何修改自定义代码片段](https://code.visualstudio.com/docs/editor/userdefinedsnippets) ｜ [Wikitext插件](https://marketplace.visualstudio.com/items?itemName=RoweWilsonFrederiskHolme.wikitext) | [了解Wikitext插件的使用方法](https://www.huijiwiki.com/p/21136) ｜ [Lua snippets for Wikimedia插件](https://marketplace.visualstudio.com/items?itemName=jeblad-3.WMFsnippets)
