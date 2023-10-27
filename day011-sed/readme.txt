1. 删除文件中所有的空行
    sed '/^$/d' filename
  在该命令中，^$表示一个空行。/pattern/d会删除匹配pattern的行

2. 删除文件中的第3行
  sed -i '3d' filename 

