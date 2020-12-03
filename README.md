# HashiTalks Brasil 2020


## Informações do evento

* Data: `03 / 12 / 2020`
* Hora: `13:15 h BRT`
* Registro / Agenda: [Link](https://events.hashicorp.com/hashitalksbrasil)
* Live stream: [Link](https://youtu.be/OWewrPSP8OQ)

## Conteúdo

* `cert`
  * Certificados TLS usados para conectar no Vault

* `config`
  * `my-policy.hcl`
    * Política do Vault usada para configurar o `AppRole`
  * `vault.json`
    * Configuração do Vault usada na demonstração

* `demo-app`
  * Aplicativo usado na demonstração
  * Execução: `npm start`

* `docker`
  * `docker-compose.yaml`
  * Arquivo YAML do Docker compose usado para rodar o Vault 1.6.0
  * `run-container.sh`
  * Script para rodar o container a partir do arquivo compose

* `vault-unsealer.sh`
  * Comandos usados para abrir (_unseal_) o Vault


## Artefatos

* Biblioteca `hashi-vault-js`
  * Última versão: `0.3.17`
  * Documentação: [Link](https://www.npmjs.com/package/hashi-vault-js)
  * GitHub: [Link](https://github.com/rod4n4m1/hashi-vault-js)
  * Instalação: `npm install hashi-vault-js --save`

* Servidor HashiCorp Vault
  * Imagem docker: `vault:1.6.0`
  * Localização: [Link](https://hub.docker.com/_/vault)
