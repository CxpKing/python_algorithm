#**Markdown file language**
---
1.标题
  *一级标题用\#表示
  *二级标题用\##表示，以此类推
---
2.列表
  *列表使用\*或+或-作为开头，后面紧跟内容
  *列表嵌套，在上一个列表下一行开头空三格即可
    *这是列表嵌套
3.字体
  *加粗：用\*\*将内容包起来
  *斜体：用\*将内容包起来
  *删除线：用\~\~将内容包裹起来
  *斜体加粗：\***将内容包裹起来
4.引用
   >这是引用内容
   >>这是引用内容
   >>>这是引用内容
5.分割线
---
***
6.超链接
[百度](http://baidu.com)
7.表格
表头|表头|表头
-|:-:|-:
内容|内容|内容
内容|内容|内容
第二行分割表头和内容。
文字默认居左，两边分别加:表示文字居中，加右为居右
8.代码
   *单行代码用一对反引号包起来
      `代码内容`
   *代码块用两对(```)引起来
      (```)
		int main(){
			printf("Hello world")
		}
	  (```)