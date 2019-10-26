# 文件整理规范

本文档列出了当前物述有栖字幕组之项目在GitHub上的管理规范。

## 分支

+ 每个正在进行的项目占用一个单独的分支。
  + *新建分支请先切换到empty分支，创建分支时选择以empty分支为基准。*
+ 已完成的项目，合并到cut/ytb&dual/bonly分支中，并删除项目分支。
+ 分支名请与工作表中的项目名保持一致。

## 文件名

1. 分段合作
   + `完成状态`+`分段时间`.ass
2. 整块熟肉
   + `完成状态`+`项目名称`.ass

+ `完成状态`将说明文字放在**全角括号**中。

例如：

<table>
 <tr>
  <td>项目名</th></td>
  <td>分段</td>
  <td>文件名</td>
 </tr>
 <tr>
  <td rowspan=7>B限-10.16-方舟歌回</td>
  <td>0-23</td>
  <td>（空轴）0-23.ass</td>
 </tr>
 <tr>
  <td>23-46</td>
  <td>（空轴）23-46.ass</td>
 </tr>
 <tr>
  <td>46-69</td>
  <td>（空轴）46-69.ass</td>
 </tr>
 <tr>
  <td>69-92</td>
  <td>（空轴）69-92.ass</td>
 </tr>
 <tr>
  <td>92-115</td>
  <td>（空轴）92-115.ass</td>
 </tr>
 <tr>
  <td>115-138</td>
  <td>（空轴）115-138.ass</td>
 </tr>
 <tr>
  <td>138-162</td>
  <td>（空轴）138-162.ass</td>
 </tr>
 <tr>
  <td>油管-9.21-烦恼商谈</td>
  <td>全</td>
  <td>（在做了）油管-9.21-烦恼商谈.ass</td>
 </tr>

</table>

## Commit

+ commit时，请在信息（GitHub Desktop中的`Summary`栏）中填入您完成工作的简要信息。
  + *在Github Desktop中，有时`Summary`会自动填写。请清空并重新填写，不要偷懒用默认信息。*
+ 每次commit后，查看commit记录（GitHub Desktop中的`History`）可对修改过的文件进行对比。