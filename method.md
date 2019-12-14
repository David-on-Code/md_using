# Markdown
## 标题
#一级标题  
##二级标题  
###三级标题  
####四级标题  
#####五级标题  
######六级标题  
  
## 字体格式强调
*强调*  (示例：斜体)  
_强调_  (示例：斜体)  
**加重强调**  (示例：粗体)  
__加重强调__ (示例：粗体)  
***特别强调*** (示例：粗斜体)  
___特别强调___  (示例：粗斜体)  
  
## 代码
`<hello world>` 
  
## 代码块高亮  
@Override  
protected void onDestroy() {  
    EventBus.getDefault().unregister(this);  
    super.onDestroy();  
}  
  
<p>这是一个普通段落：</p>

<pre><code>
@Override  
protected void onDestroy() {  
    EventBus.getDefault().unregister(this);  
    super.onDestroy();  
}  
</code></pre>
  
## 表格 （建议在表格前空一行，否则可能影响表格无法显示）
  
表头  | 表头  | 表头
---- | ----- | ------ 
单元格内容  | 单元格内容 | 单元格内容
单元格内容  | 单元格内容 | 单元格内容 
  
## 引用图片
![图片名称](https://www.baidu.com/img/bd_logo1.png) 
## 链接
[链接名称](https://www.baidu.com/)  

## 列表
1. 项目1   
2. 项目2   
3. 项目3   
  * 项目1 （一个*号会显示为一个黑点，注意⚠️有空格，否则直接显示为*项目1）  
  * 项目2   
  
## 换行
  
## 首行缩进
在开头的时候，先输入这个，然后紧跟着输入文本即可。分号也不要掉。  
&#160; &#160; &#160; &#160;Hello!
  
  
## 引用
> 第一行引用文字   
> 第二行引用文字 

# Github md 插入公式  
安装chrome的插件 GitHub with MathJax 可以在你自己的浏览器解析Latex公式，但是没装插件的人看着还是源码。xuan!!!  
[牛]https://github.com/orsharir/github-mathjax  
莫名其妙！！！  
$$
y_{i} \cong \widetilde{Y}_{i}=S\left(x_{i}^{1}, \ldots, x_{i}^{T} ; \theta\right)
$$
  
$$
y_{i} \cong \widetilde{Y}_ {i}=S\left(x_{i}^{1}, \ldots, x_{i}^{T} ; \theta\right)
$$  
![error](https://github.com/David-on-Code/md_using/blob/master/e.png)  
![right](https://github.com/David-on-Code/md_using/blob/master/r.png)  
GitHub公式编辑正确与否，检查公式 是否有斜体存在!!!!，一般添加空格即可解决！  
