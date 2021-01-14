# elasticsearch-deployment
Automated and manageable deployment of elasticsearch

## How-To

```
ansible-playbook -k playbooks/full_install.yml --inventory-file=inventory/prod_platform/ -u <username_of_nodes>
```
also you can apply for only specific tags with 
```
--tags "<tag_name_2>,<tag_name_2>"
```
or you can skip specific tags with 
```--skip-tags "<tag_name_2>,<tag_name_2>```

## TODO:
* [x] Elasticsearch
* [x] Elasticdump
* [x] Head plugin
* [x] Monit
* [ ] Kibana deployment
* [ ] Logstash distributed deployment
