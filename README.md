# td-agent
## How to install td-agent

`yum install curl-devel`  
`yum -y install gcc libcurl-devel`  
`curl -L http://toolbelt.treasuredata.com/sh/install-redhat-td-agent2.sh | sh`  

/usr/sbin/td-agent-gem install fluent-plugin-multiprocess
/usr/sbin/td-agent-gem install fluent-plugin-filter
/usr/sbin/td-agent-gem install fluent-plugin-parser
/usr/sbin/td-agent-gem install fluent-plugin-typecast
/usr/sbin/td-agent-gem install fluent-plugin-elasticsearch
