# idea误删iml文件后项目整体报红
## 此种情况可能会出现在其他人员将.idea或者.iml文件上传后,拉取代码时覆盖本地.idea文件或者.iml文件

解决办法:
生成.iml文件:mvn idea:module
生成.ipr文件: mvn idea:project
生成.iws文件: mvn idea:workspace
