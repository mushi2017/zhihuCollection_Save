zhihu_to_evernote
=================

将知乎收藏自动发送到Evernote/印象笔记中
=================
将知乎收藏问答页面的所有问答发送到Evernote/印象笔记中、
支持自己的知乎收藏或他人的知乎收藏。
因为Evernote/印象笔记可以直接将收到的附件转为笔记内容、
所以我直接将知乎问答通过html格式的邮件发送到Evernote中。

由于需要发送邮件，所以需要SMTP服务器以及发送邮件的账号和密码。
先将所需内容填写到config.ini配置中的对应位置即可

=======================================================
使用说明：
将config.ini和zhihu_to_evernote.py文件下载到同一个目录下
修改config.ini里面的内容为自己真实信息
然后python zhihu_to_evernote.py即可
