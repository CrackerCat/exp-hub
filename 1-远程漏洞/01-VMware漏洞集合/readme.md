1、尝试获取目标版本  
2、通过版本比对表查看Build Number对应的版本：https://kb.vmware.com/s/article/2143832  
3、得知目标版本是否在漏洞影响范围内  

### CVE-2015-2342
漏洞参考链接：https://vulmon.com/vulnerabilitydetails?qid=CVE-2015-2342&scoretype=cvssv2  
```
The JMX RMI service in VMware vCenter Server  
5.0 before u3e  
5.1 before u3b  
5.5 before u3  
6.0 before u1  
does not restrict registration of MBeans, which allows remote malicious users to execute arbitrary code via the RMI protocol.
```
利用参考链接：https://github.com/mogwaisec/mjet  
