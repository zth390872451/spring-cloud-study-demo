1、我发现一个问题：spring cloud config的  这个属性值配置 ：如果是在码云上 和在github上， 拉取的文件不一致，也是醉了。码云上值会拉取一个 application.properties
2、特别注意  svn 环境 需要 引入 SVN jar包
<groupId>org.tmatesoft.svnkit</groupId>
<artifactId>svnkit</artifactId>