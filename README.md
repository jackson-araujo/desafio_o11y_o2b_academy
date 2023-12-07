Desafio proposto para validar os conhecimentos adquiridos no curso de Introdução à Observabilidade - O2B Academy 
(https://github.com/patrickjcardoso/desafio_o11y).


Criar um ambiente de Observabilidade usando Prometheus e Grafana, para monitorar uma aplicação de exemplo.

Nesse projeto foi utilizado o Killercoda para acesso a uma máquina Ubuntu, utilizada para publicar uma aplicação web baseada em Pyhton, utilizei o docker-compose para criação/inicialização/administração dos contêiners com: Prometheus, Grafana e Alertmanager.

Obs.: realizada a criação de um script, baseado em shellscript, bem simplista e funcional, para auxiliar na otimização e confiabilidade do projeto. Efetua a criação dos diretórios e arquivos, assim como a importação das configurações para a realização do projeto (Ambiente de Observabilidade).

Em poucos minutos é possível visualizar o projeto funcional, com:

Prometheus: coletando métricas e monitorando o ambiente.


Grafana: Exibição dos painéis, já com datasources e dashboards,  importados em sua inicialização.


Python: aplicação web com funcionalidade para simular erros, auxiliando para que a regra de alerta seja executada. 


Alertmanager: recebendo o alerta conforme regra e notificação via Webhook-site e Discord.



Obs: 
# Antes de inicializar esse arquivo é necessário criar um arquivo com o nome jks.sh, localizado em /root/

# Em seguida defina permissão de execução para o usuário proprietário do arquivo: chmod u+x jks.sh

# Copie esse Script e cole o conteúdo dentro do arquivo: jks.sh

# Em seguida execute o script: ./jks.sh
