# 作用

批量下载邮件中的附件，将附件保存到邮件名字的目录中

# 已知bug

当邮件中有多个附件，且附件的格式为不常见格式时，有一定概率的跳过下载情况，目前不清楚原因。

对新浪邮箱测试时，当下载了20个左右后，会被服务端重置连接，猜想是服务器的防攻击机制导致。

# 说明

python2.7  

库中的 email module 为标准库中的 email module  