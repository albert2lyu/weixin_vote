# weixin_vote

### run steps
- add config.py
```
DOMAIN = ''
DB_HOST = ''
DB_NAME = ''
DB_USER = ''
DB_PWD = ''
```
- run `index.py`

### feature
- tornado
- torndb(no ORM!): http://torndb.readthedocs.org/en/latest/#
- for sae
- multiple accounts suport

### todo
- [ ] �Զ���ȡ���ںŻ�����Ϣ
- [ ] �����롢ע�����Զ���ʱ����

### libs
- tornado
- MySQL-python
- pycrypto
- httplib2

### dev env
- use TUNNEL : http://www.tunnel.mobi/
```
ngrok -config ngrok.cfg -subdomain weixin_vote 8080
```

### tmp note
- style: http://dushu.xiaomi.com/#1