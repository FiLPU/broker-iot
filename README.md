Broker MQTT para projetos IoT – configuração modelo e educacional
# Broker-IoT

Projeto modelo de Broker MQTT para aplicações IoT.

Este repositório contém apenas configurações de exemplo.
Antes de usar, altere usuários, senhas e permissões.
Hardware usado: Orange pi zero 3, use qualquer de sua preferência, consulte documentações.
## Estrutura esperada pelo Backend

O backend deste projeto verifica a existência do diretório:

/etc/mosquitto/

E espera encontrar os seguintes arquivos:

- mosquitto.conf
- passwd
- mosquitto.acl

Neste repositório, esses arquivos são fornecidos apenas como
exemplos na pasta `mosquitto/`.

Antes de executar o backend:
Copie os arquivos `.example`, renomeie e ajuste conforme
seu ambiente.
