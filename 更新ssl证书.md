# 更新ssl证书
今天发现服务器的ssl证书验证失败，发现是过期了。于是疯狂搜索速成更新证书。

	acme.sh --renew -d <domainname> --force
	acme.sh --renew -d xingfeng1.grate.ru --force
	~/.acme.sh/acme.sh --renew -d xingfeng1.grate.ru --force
	~/.acme.sh/acme.sh --set-default-ca  --server  letsencrypt