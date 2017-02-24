# dragSort
基于react 的拖拽并自动排序
=======================================================================================================
| 属性          | 说明                                                      | 默认值|   类型   |
| ------------- |:--------------------------------------------------------:|:-----:|:-------:|
| clickElement  | 点中的元素                                                 |      |function |
| dragElement   | 拖拽的持续过程                                             |       |function |
| dragOver      | 拖拽结束（松开鼠标的时候）                                  |       |function |
| moveStop      | 每一个元素运动停止了以后（只要是点一下就会有 moveStop）       |       |function |
| time          | 运动时间                                                   | 500ms | string  |
| type          | 运动类型 ease-out减速 默认  ease-in加速 linear匀速          |ease-out|  string |
