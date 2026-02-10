# deploying-zabbix

Este projeto tem como objetivo documentar e versionar o **provisionamento do Zabbix utilizando Docker e Kubernetes**, seguindo boas práticas de infraestrutura, automação e organização por versão.

A branch `main` funciona como uma **apresentação geral do projeto**.  
Cada versão específica do Zabbix é mantida em sua **própria branch**, garantindo clareza, histórico e facilidade de manutenção.

---

## 🎯 Objetivo do Projeto

- Demonstrar como provisionar o **Zabbix** de forma reproduzível
- Utilizar **Docker** e **Kubernetes** como base de deployment
- Manter **uma branch por versão do Zabbix**
- Servir como material de estudo, laboratório e referência prática
- Evoluir o projeto conforme novas versões do Zabbix são lançadas

---

## 🌱 Estrutura de Branches

A organização do repositório segue o padrão:

- `main`  
  - Apresentação do projeto
  - Documentação geral
  - Visão arquitetural
  - Direcionamento para as branches de versão

- Branches por versão do Zabbix  
  Cada branch contém **apenas os arquivos e instruções daquela versão específica**: 5.0 LTS, 6.0 LTS, 7.0 LTS


Exemplo:
- `5.0 LTS` → Zabbix 5.0 com Docker / Kubernetes
- `7.0 LTS` → Zabbix 7.0 com Docker / Kubernetes

---

## 🧱 O que você vai encontrar em cada branch de versão

Cada branch de versão pode conter, por exemplo:

- Docker Compose (quando aplicável)
- Manifests Kubernetes (Deployment, StatefulSet, Service, Ingress, etc.)
- Configuração de banco de dados (MySQL / PostgreSQL)
- Ajustes de volumes persistentes
- Configurações específicas da versão do Zabbix
- README próprio com instruções detalhadas

---

## 🐳 Tecnologias Utilizadas

- **Zabbix**
- **Docker**
- **Docker Compose**
- **Kubernetes**
- **Helm** (futuramente, se aplicável)
- **PostgreSQL / MySQL**
- **NGINX / Ingress Controller**

---

## 🚧 Status do Projeto

🔧 Em desenvolvimento  

Este projeto está em constante evolução e será atualizado conforme:
- Novas versões do Zabbix
- Melhorias na arquitetura
- Aprendizados práticos em ambientes reais

---

## 📌 Como usar este repositório

1. Leia este README na branch `main`
2. Escolha a versão do Zabbix desejada
3. Troque para a branch correspondente:
 ```bash
 git checkout 7.0
 ```
4. Siga as instruções específicas daquela versão

## 📚 Público-alvo

- Estudantes de infraestrutura
- Administradores de sistemas
- Profissionais de DevOps
- Pessoas que querem aprender Zabbix na prática
- Ambientes de laboratório e estudo

## 📝 Observações

- Cada versão do Zabbix pode ter diferenças significativas de configuração
- Nunca misture versões na mesma branch
- A documentação de cada branch é a fonte de verdade daquela versão

