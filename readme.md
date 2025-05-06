# 我的 LuaLaTeX 项目模板

前阵子折腾 HUGO 和 MathJax , 感觉在创建大型文档上还是不如 LaTeX 。不过 HUGO 的项目管理给了我一些启发 。

几个文件夹的作用 : 

- `.vscode` : vscode 插件 latex workshop 配置
- `content` : 文章内容
- `layouts_theme` : 默认主题配置 , 其中
  - `use.tex` 用于引用包
  - `set_call.tex` 用于设置 Github callouts 样式
  - `set_code.tex` 用于设置代码块样式
  - `set_code_fvextra01.tex` 为[此答案](https://tex.stackexchange.com/questions/741923)的第一个版本
  - `set_code_fvextra02.tex` 为[此答案](https://tex.stackexchange.com/questions/741923)的第二个版本
- `layouts_custom` : 额外的主题配置
- `static` : 存放图像 , 代码等内容

感谢 tex.stackexchange.com 上各位专家提供的帮助 。下面是我提过的问题 :

- [minted pygments dark style do not have optimization for LaTeX syntax](https://tex.stackexchange.com/questions/742042)
- [Is there a good way to make tcblistings highlight lines and the linenumber at the same time?](https://tex.stackexchange.com/questions/741923)
- [Is there any goodway to make tcolorbox overlay cover the box content?](https://tex.stackexchange.com/questions/741872)

此外正在研究 @thruston 的 [Drawing-with-Metapost](https://github.com/thruston/Drawing-with-Metapost)