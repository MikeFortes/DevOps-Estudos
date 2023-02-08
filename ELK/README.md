![](https://www.paragyte.com/img/elk%20Banner.jpg)
# Anotações de estudo

## Instalação do ambiente
Ambiente instalado em um Ubuntu Server, mas operacional em outras distribuições.

### Atualizndo o ambiente
* yum update
* apt-get install update
### Adicionando repo oficial ELK e exportando chaves 
* wget -qO - https://artifacts.elastic.co/GPG-KEY-elasticsearch | sudo apt-key add -
* trusted.gpg.d
* sudo apt-get install apt-transport-https
* echo "deb https://artifacts.elastic.co/packages/7.x/apt stable main" |
* sudo apt-get update && sudo apt-get install elasticsearch
### Configuração inicial 

* vim /etc/elasticsearch/elasticsearch.yml

Descomentar o parametro network.host (caso use um lab, deixe 0.0.0.0)&nbsp;

Descomentar o parametro discovery.seed.host ["127.0.0.1"]
&nbsp;

Descomentar  e alterar para cluster.initial_master_noes ["node-1"]
&nbsp;


## Contato

- Linkedin: [Michael Fortes](https://www.linkedin.com/in/mikefortes)
- Twitter: [@mikes_script
](https://twitter.com/mikes_script)
- Email: mromeiro.f@gmail.com

Project Link: [https://github.com/MikeFortes/DevOps-Estudos](https://github.com/MikeFortes/DevOps-Estudos)