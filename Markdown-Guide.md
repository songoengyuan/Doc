1. 编辑器选择
可以使用VSCode，这是微软官方出品的文本编辑器，体积小，但功能强大，而且跨平台，在Mac上也有，所以使用体验比较统一。
直接访问VSCode网站，下载地址：https://code.visualstudio.com/Download

2. 安装Markdown高级预览插件
VSCode自带Markdown预览功能，但只支持Markdown基本语法，建议安装Markdown Preview Enhanced
直接在VSCode的插件安装中选择此插件，安装即可。

3. 常用Markdown语法要素

```md {.line-numbers}
===               //文章大标题，需放在标题文字下方
---               //文章副标题，需放在标题文字下方
# H1              //一级标题
## H2             //二级标题
###### H6         //六级标题
*Text*            //斜体文字
**Text**          //粗体文字
~~Text~~          //带删除线的文字
==Text==          //黄色高亮标记(marked)
* Text            //无序列表
- Text            //无序列表
1. Text           //有序列表，序号可全是1
![Alt Text](url)  //图片
[link Text](url)  //链接
> Text            //引用
***               //分隔线
---               //分隔线
___               //分隔线
`Text`            //行内代码
                  //代码片断
- [x] Text        //任务列表
|A|B|C|           //表头
|:---|:---:|---:| //表格定义，左对齐、居中对齐、右对齐
E = M*C^2^        //上标
H~2~O             //下标 
Text[^1]          //脚注符号
[^1]: Description //脚本描述，必须与脚本符号成对出现

```

4. Markdown Preview Enhanced的高级功能
请访问：https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/


5. 更改字体配置
安装字体: Microsoft-YaHei-Mono

打开文件/首选项，在右侧添加以下配置。
{ 
//-------- Editor configuration -------- 
// Controls the font family.  
"editor.fontFamily": "Microsoft YaHei Mono",
"editor.fontSize": 15,
}






