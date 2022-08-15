# grid网格

## grid网格概念
css网格是一个用于web的二维布局系统。利用网格，你可以轻松的把内容按照行和列的格式进行排版。另外，网格还能非常轻松的实现一些复杂的布局。

### 重点
1. 定义网格及fr单位
2. 合并网格及网格命名
3. 网格间隙及简写
4. 网格对其方式及简写
5. 显示网格与隐式网格
6. 基于线的元素放置
7. 子项对其方式
8. repeat（）与minmax（）
9. 比定位更方便的叠加布局
10. 多种组合排列布局
11. 杉格布局
12. 容器自适应行列布局

## grid容器
justify-items, align-items, place-items, justify-content,align-content, place-content,grid-auto-flow,grid-auto-rows,
grid-auto-columns,grid-itemplate-rows,grid-template-columns,grid-template-areas,grid-template,grid-row-gap,grid-column-gap,grid-gap

## 定义网格行 grid-template-rows 
基于网格行和列的维度，去定义网格线的名称和网格轨道的尺寸大小
## 定义网格列 grid-template-columns
基于网格行和列的维度，去定义网格线的名称和网格轨道的尺寸大小

## fr 比例均分

## grid-template-areas  合并单元格
使用命名方式定义网格区域，需配合grid-area属性进行使用

## grid-template 
grid-template-rows，grid-template-columns，grid-template-areas属性的缩写

# 网格间隙及简写   简写方式同样适合弹性布局
    grid-row-gap grid-column-gap grid-gap
    用来设置元素行列之间的间隙大小，推荐row-gap,column-gap,gap

    row-gap: 行的复合样式
    column-gap：列的复合样式
    gap： 总的复合样式

## 子项在网格中的对其方式
justify-items 水平方向, align-items 垂直方向, place-items 复合方式 默认是stretch

## 指定了所有网格在grid容器中的对齐方式
justify-content, align-content, place-content
容器要比单元格大才能指定对齐方式

## 显示网格与隐式网格 
grid-auto-flow，grid-auto-rows,grid-auto-columns
指定在显示网格之外的隐式网格，如何排列及尺寸大小

## grid子项
justify-self,align-self,place-self,grid-row,grid-column, grid-area,grid-column-start,grid-column-end,grid-row-start,grid-row-end


## 基于线的元素放置

## grid-column-start,grid-column-end,grid-row-start,grid-row-end
表示grid子项所占据的区域的起始和终止位置，包括水平方向和垂直方向

## grid-row grid-column 基于线对应位置的缩写方式，通过 / 作为分割
grid-column : 2 / 3  grid-row: 2 / 3

## grid-area 缩写
grid-row-start,grid-column-start,grid-row-end以及grid-column-end属性的缩写，以及额外支持grid-template-areas设置的网络名称

## 子项的对齐方式 （justify-start, align-self, place-self）
跟place-item用法相同，只不过是操作指定的子项

## repeat()与minmax（）
repeat()方法及auto-fill可选值，指定可重复的数值
repeat 列或者行重复
auto-fill 自动产生网格的个数

minmax（）方法，设置最小值和最大值的范围






