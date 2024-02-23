# baculum-cn
bacula web gui 中文

baculum 官方没有中文包
messages.po 为翻译后的中文包

1、在 lang 目录下新增 cn 目录
/var/www/bacularis-app/protected/vendor/bacularis/bacularis-web/Web/Lang/cn/messages.po

2、新建messages.po

3、基于 po 文件生成 mo 文件
msgfmt -o messages.mo messages.po

