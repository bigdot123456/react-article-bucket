### 前言
本章节主要提供一些字符串操作相关函数，通过他们可以快速介入开发，而不用为工具函数发愁。欢迎star

### API
- encodeScript(string)

对html字符串内部的script标签进行编码。

- getQueryString(name,isSpa)

获取URL中的特定查询字符串，第二个参数表示是否是单页应用。

- compare(a,b)/isObjEqual

判断两个对象的是否完全相同。

- deepCopy(obj)

深度拷贝一个对象。

- generateRandomKey

得到一个唯一的key。

- getFirstItemRecersively(array,key)
 
递归获取这个数组中最深层次的含有key的对象。
 
- decodeHTMLEntities(string)

对html实体反解码。

- isEmptyObject
  
空对象实体。

- uniqueBy

用于通过某一个属性来去重。

- compare(property,asc=true) 
 
对象数组按照某一个字段排序。**用法为**:groupRule.sort(compare('priority'))

- type(obj)
  
 判断一个变量的真实数据类型，与jQuery的type方法一致