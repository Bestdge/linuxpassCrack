# linuxpassCrack
To decrypt the /etc/paawd of linux

【hash字典爆破】
Unix口令破解机，破解/etc/passwd中的账号加密的口令，dictionary.txt是口令字典，passwords.txt是/etc/passwd内容；

思路：使用/etc/passwd密码前两个字符作为salt，再和字典进行crypt()函数加密，进行比对。

usage:python linuxpassCrack.py
