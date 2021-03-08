# 思源主题: mixture(light)
![preview](preview.png)

主题主颜色为青色，主字体为思源黑体，代码字体为Fira Code，深色主题见[Mixture Dark](https://github.com/Achuan-2/siyuan-themes-mixture)

❤特色
- 这是一个追求极致的主题
- 目前文件未保存的时候，标签页字体为灰色，保存成功为粉色
- 本主题暂时**隐藏了标签页的文件图标**
- 增大了当前标签页的最大文字宽度
- 点击任务列表有动效，完成的任务列表样式暂定以颜色减淡来取代删除线（删除线太不优雅了，这样也可以多一个选择，可以自行添加），并对特殊样式包括图片、高亮、加粗、超链接、代码块等也进行一定减淡、颜色更改处理
- 弹出窗口有左右展开动效
- 优化了对行内公式和公式块的大小问题


⚠前排提示：
- 如果需要**更改字体**，请在主题文件夹下的 theme.css 中，`--b3-font-family:'SourceHan',... ` 将思源黑体删除、置后或更改
- 任务列表完成默认无删除线，如果需要完成任务列表自动添加的删除线，可以自行添加删除线（`Ctrl+D`），或者自行修改主题：搜索"完成的待办事项删除线",将`/* text-decoration: line-through; */`取消注释注释
- 由于个人习惯一级标题作为文章标题索所以默认为居中，可能对习惯把一级标题作为正文标题的童鞋不太友好，可以搜索`标题样式`，将h1`.vditor-reset h1 {text-align: center;...}`中的`text-align: center;`改为`/* text-align: center; */`以注释，并将`.vditor-reset h1:after {...}`样式全部删掉

---

## v0.2.2/2021-3-8

- 调整引用块边框颜色
- 块旁边显示的数字加边框
- 一级标题去掉下边框保持居中，二级横线颜色调整，三级竖线调细
- 列表间距调整
- 超链接添加下划线
- 调整数学公式块大小
- 修复预览模式的行内代码左侧凸出的问题
- 调整块引用卡片的阴影
- 添加块引用悬浮动画
  
## v0.2.1/2021-3-8

- 多窗口当前页面标签页添加底框
- 对待办列表中的代码块复制按钮进行透明度调整
- 调近代办样式的距离
- 调整标签与普通文字距离
- 块引用下划线间距调整
- 对完成的待办事项内容全部调整透明度

## v0.2.0/2021-3-7

又双叒叕更新了，这是一次大刀阔斧的更新，提出追求极致的口号！😏
- 鉴于原先阿里巴巴普惠体版权问题，**更改中文主字体为思源黑体**
- 修复因为标签页与上方选项栏的间距导致主题会出现**两个滑块的问题**
- **修正调整字号后主题待办列表checkbox无法完全覆盖checkbox基本样式的bug**
- 代码块渲染目前**支持显示部分语言名称**，但语言名称显示会随着滑块移动，待完善
- 修复将body设置了perspective造成的**字体模糊**，**修改窗口弹出动效**为Y轴翻转
- 调整标签页字体放大效果，**调整选中的标签页最大文字宽度**
- **减小文件树列表间距**
- 对标题样式代码、标签等样式进行重写，使得其能**适配不同字号大小**
- **减小阴影**：图片、嵌入卡片
- 再次调整**表格颜色**
- 调整==高亮==样式, 对完成的待办列表中的高亮样式进行调整
- 调整块引用下划线与文字的间距
- 调整完成的待办列表中的代码样式透明度
- 调整多窗口的边框颜色
- 修改标签样式，将标签样式调淡，圆角增大
- 分别针对MathJax行内公式和公式块大小进行优化（之前只设置KaTex的）
- 初步对主题css即时渲染行内元素样式的颜色代码进行优化，部分使用变量
- 标签页margin-left改为margin-right

## v0.1.8/2021-3-4

好了，我改不动了，要是没什么大问题近期就不改主题了，毕竟自己笔记都没咋写，光弄花架子了
- 分别更改行内公式和公式块大小
- 代码块和公式块编辑缩进，同时考虑到有行号时代码块的缩进。（摸索半天，太折腾了，这边改完那边变）
- 减小图片阴影
- 标签页样式更改，未选中标签页与选中标签页有背景颜色和字体大小及颜色区别，增大标签页之间的距离

## v0.1.7/2021-3-4

- 改进行内代码的css代码，避免其影响代码块编辑区
- 对代码块编辑区样式进行修改
- 对行内公式编辑样式进行修改
- 去掉表格阴影

## v0.1.6/2021-3-4

- 修正行内公式块有多余空间的问题
- 对已完成代办事项中的加粗、斜体、删除线、超链接进行优化，事项中含有的图片透明度设置为60%，鉴于原先默认设置的删除线可能不方便查看，暂时决定取消，可以自行添加删除(Ctrl+D)，或者自行修改主题,搜索"完成的代办事项下划线",`/* text-decoration: line-through; */`取消注释
- 更改h3标题与上下文的间距
  
## v0.1.5/2021-3-3

- 修复从edge复制的超链接，形如[思源笔记更新日志(ld246.com)](https://ld246.com/tag/siyuan-announcement)，分多块hover高亮的问题
- 将表格颜色减淡
- 将图片阴影调小

## v0.1.4/2021-3-3

- 去除选中标签页的背景色
- 仿照Lavender设置界面动效，更改设置的关闭按钮颜色和hover背景
- 仿照Passion设置选中项的圆角
- 去除代码块、引用块的阴影
- 更改代码块和引用块颜色
- 更改弹出菜单样式
- 更改编辑区上方工具栏阴影

## v0.1.0/2021-3-2
- 将Mixture Dark 暗色主题的样式照搬并进行修改