## 目录

- work2
  - demo.html（在chrome上运行）
  - jquery-easyui-1.3.3/themes/default/easyui.css（调用的外部框架）
  - jquery-easyui-1.3.3/themes/icon.css
  - jquery-easyui-1.3.3/demo/demo.css
  - jquery-easyui-1.3.3/jquery.min.js（调用的js函数）
  - jquery-easyui-1.3.3/jquery.easyui.min.js
  - jquery-easyui-1.3.3/locale/easyui-lang-zh_CN.js

## 使用方式

- 下载work2到本地，解压后文件本地，用chrome打开demo.html,在左侧文本框输入文本并且有输入提示。

  学术家族树以文本形式输入，点击展示成树。
  
## 文本格式

  ### 输入：
  
  学术家族树以文本形式输入，点击展示成树即可生成，考虑学术家族树的文本格式是这样的：

  导师：张三

  2016级博士生：天一、王二、吴五

  2015级硕士生：李四、王五、许六

  2016级硕士生：刘一、李二、李三

  2017级本科生：刘六、琪七、司四

  刘六：JAVA、数学建模

  李二：字节跳动、京东云
  

  其中，"导师："，"级博士生："，"级硕士生："，"级本科生："和"、"当做关键词处理；若有多组输入，中间空一行。

## 输出：

- 树的节点，鼠标点击后是可以缩放的。同时，支持呈现多棵树并存、两棵关联树共存等形式。

  在右侧家族树下会显示可缩放的树状结构，即生成的家族树。
