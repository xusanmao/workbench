#鹏博士工作台 社区导入文件格式说明

- 文件名以.yml为扩展名, 如 "community.yml"

- 文件格式为纯文本文件，并以utf-8编码保存，且不要有bom头。

- 格式内容如下
```yml
#这是城市名称
城市: 深圳 
所有社区:
  - 社区: 
      #这是社区名称 不要有重名，否则可能会被过滤掉
      名称: 岸芷汀兰  
      #部门名称 可以有多个，如果有一个就留一个
      #只写最终部门就可以，上级部门会自动添加
      部门: 
      	 - 科苑服务站
      	 - 南头服务站
  - 社区: 
      #注意如果名称中有特殊符号，请用英文'引号引起，引号引起中如果显示'号，请使用''
      名称: '岸芷 # : - '' "  汀兰'  
      #部门名称 可以有多个，如果有一个就留一个
      #只写最终部门就可以，上级部门会自动添加
      部门: 
      	 - 科苑服务站
      	 
```
- 了解文件格式后#号开头的行可以去掉， 注意格式中:号及-号都为英文半角

[返回列表](README.md)
