# ZJXMLHelper
A parser of XML and XML generator

该工具类方便把XML转换成我们熟悉的字典或者把字典对象生成对应的XML数据,在生成XML的过程中使用了函数递归调用,因此不必担心字典对象中层级嵌套的问题,当然数据量如果过大,必然会有效率上的问题.




### 说明:
该工具的XML解析是参照XMLDictionary的解析方式,在处理根节点以及和根节点相关标签时,使用了自定义的一些属性以及加了固定的前缀(__name,_tag),这样为了能把XML数据更加完整的放在我们的字典对象中,实际中有些数据可能不需要,则根据自己的需要自己取舍.

[XMLDictionary](https://github.com/nicklockwood/XMLDictionary)

## ZJXMLHelperDemo说明
1.该Demo主要依靠于ZJXMLHelper.framework这个库,这个库是我自己写的一个库,牵扯到某些东西,所以没有把源码公开,使用方法以及相关API上面都有注释,希望能助于各位同仁.

2.该类中的主要方法以及使用说明,请参照
`ZJXMLParseHelper`这个Class.

3.如果有疑问或者需要源码做进一步的自定义处理或者开发研究,请在下方留言,我会在看到后的第一时间回复,谢谢.

4.项目中的ZJXMLHelper.framework是我把打出来的真机库和模拟器库合并的库,支持真机和模拟器环境.

5.该Demo中的演示了几个简单的例子,各位读者可以通过此Demo,更能清晰地理解该工具类,具体请查看该Demo中的事例.

 